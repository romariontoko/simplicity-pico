
# IT Administrator Assignment - Simplicity Project

# IT Administrator Assignment - Simplicity Project

## Introduction
This assignment involves creating and hosting a website using the pico.sh service. The goal is to upload the `simplicity.html` webpage to a serverless hosting provider and create a GitHub repository to store our files.

## Steps Taken:

1. **Creating an SSH Key**:
   We created an SSH key using the ED25519 method to connect to the pico.sh service. The steps for creating the SSH key can be found in the official pico.sh documentation.

2. **Creating an Account on Pico.sh**:
   We created our account on the pico.sh platform to host our website.

3. **Uploading the HTML File**:
   Using the `rsync` tool, we uploaded the `simplicity.html` file to the pico.sh platform, which is now hosted at the following URL: `https://romariontoko-site.pgs.sh/simplicity.html`.

4. **Creating a GitHub Repository**:
   We created a GitHub repository named `simplicity-pico`, where we stored the `simplicity.html` file and the `README.md` file.

## Execution Instructions
To replicate this process, follow the steps below:

1. Create an account on [pico.sh](https://pico.sh).
2. Create an SSH key using the following command:
   ```bash
   ssh-keygen -t ed25519	# simplicity-pico
simplicity-pico
