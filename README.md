# rr
Run a script remotely via ssh.

Examples:

    echo "127.0.0.1" | rr -u centos /path/to/script.sh

In conjunction with [awsip](https://github.com/ashatch/awsip):

    awsip cf my-stack | rr -u ec2-user /path/to/script.sh

# Installation

Install via brew.

    brew tap ashatch/homebrew-repo
    brew install rr
