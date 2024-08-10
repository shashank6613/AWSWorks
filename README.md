Set the environment variables in your shell or operating system. These variables will be accessed by Terraform during execution.

For example, if you’re using AWS, you can set the following environment variables:

In Linux terminal

export AWS_ACCESS_KEY_ID="your-access-key-id"
export AWS_SECRET_ACCESS_KEY="your-secret-access-key"
export AWS_SESSION_TOKEN="your-session-token" # Optional, for temporary credentials

Unsetting Environment Variables in Unix/Linux/macOS

unset AWS_ACCESS_KEY_ID
unset AWS_SECRET_ACCESS_KEY
unset AWS_SESSION_TOKEN  # If you use session tokens
