# Automating Documentation Workflows with Python

:date: April 15, 2026
:tags: automation, Python, docs-as-code

One of the most impactful things I did at Synopsys wasn't writing documentation — it was automating the processes around it. I developed Python and Bash scripts to automate OLH (Online Help) build check-ins, reducing manual effort by 40%.

Here's how I approached it.

## The Problem

Every time we updated documentation, the OLH build process required several manual steps:

1. Build the help files from DITA-XML source
2. Run validation checks
3. Check the output into Perforce
4. Verify the build succeeded
5. Notify the team

This process took 30+ minutes per cycle and was prone to human error.

## The Solution

I wrote a Python script that:

1. **Triggers the Build:** Calls the DITA-OT (DITA Open Toolkit) with the correct parameters.
2. **Validates Output:** Checks that all expected files were generated without errors.
3. **Automates Check-in:** Uses Perforce command-line tools to commit the build output.
4. **Notifies the Team:** Sends a confirmation message with build status.

### Example Script Structure

```python
import subprocess
import sys

def build_olh(project_path):
    """Build OLH from DITA-XML source."""
    result = subprocess.run(
        ["dita", "-i", f"{project_path}/main.ditamap", "-f", "htmlhelp"],
        capture_output=True,
        text=True
    )
    if result.returncode != 0:
        print(f"Build failed: {result.stderr}")
        sys.exit(1)
    print("Build successful")

def check_in_to_perforce(output_path, changelist):
    """Check OLH output into Perforce."""
    subprocess.run(["p4", "add", f"{output_path}/..."])
    subprocess.run(["p4", "submit", "-d", f"OLH build: {changelist}"])
    print("Checked in successfully")

build_olh("/path/to/project")
check_in_to_perforce("/path/to/output", "Automated OLH build")
```

## The Results

- **40% reduction** in manual effort
- **Zero build errors** from human mistakes
- **Faster turnaround** from content update to published help
- **More time** for actual documentation work

## Key Takeaways

1. **Identify Repetitive Tasks:** If you do it more than three times, automate it.
2. **Start Simple:** Begin with one workflow and expand from there.
3. **Use What You Know:** I knew Python, so I used Python. Start with the tools you're comfortable with.
4. **Measure Impact:** Track time saved to justify further automation efforts.

## The Bottom Line

Technical writers who can automate are exponentially more valuable. You don't need to be a software engineer — you just need to think like one when it comes to your own workflows.

---

*Want to discuss documentation automation? Find me on [LinkedIn](https://linkedin.com/in/himani698/) or [GitHub](https://github.com/Himani99).*
