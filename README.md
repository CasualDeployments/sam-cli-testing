# sam-cli-testing

Messing around with SAM CLI

## Tools

1. AWS CLI (Already installed on Amazon Linux 2023 AMI 2023.7.20250512.0 x86_64 HVM kernel-6.1)

    ```bash
    aws --version
    ```

1. Git

    ```bash
    sudo yum install -y git
    git --version
    ```

1. Homebrew

    ```bash
        /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
        echo >> /home/ssm-user/.bashrc
        echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> /home/ssm-user/.bashrc
        eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"
        brew --version
    ```

1. SAM CLI and Python@3.12

    ```bash
    brew install aws-sam-cli python@3.12
    sam --version
    python3.12 --version
    ```
