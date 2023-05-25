0x0F. Load balancer

Context: You have been given two additional servers: gc-[STUDENT_ID]-web-02-XXXXXXXXXX and gc-[STUDENT_ID]-lb-01-XXXXXXXXXX. The goal is to improve the web stack by introducing redundancy for the web servers. This will enable handling more traffic by doubling the number of servers and enhancing the reliability of the infrastructure. In the event that one web server fails, the second server will be available to handle requests.

To accomplish this, you need to write Bash scripts that automate the configuration process on brand new Ubuntu servers, aligning with the project requirements.

Requirements:
- Use one of the allowed editors: vi, vim, or emacs.
- Ensure your scripts are compatible with Ubuntu 16.04 LTS.
- All script files should end with a new line.
- Include a mandatory README.md file at the project's root folder.
- Make sure your Bash script files are executable.
- Your Bash scripts should pass Shellcheck (version 0.3.7) without any errors.
- The first line of each Bash script should be #!/usr/bin/env bash.
- Provide a comment as the second line of each Bash script, explaining the purpose of the script.
