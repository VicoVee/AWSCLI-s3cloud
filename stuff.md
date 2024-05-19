# Command Format
`aws [options] [command] [subcommand] [[subcommand] ...] [parameters]`

Before running commands, sign into your users by running: `aws configure`
- Copy the token from AWS Cloud Account and paste the Access Key and Secret Access Key
- (Personally) Add default region as `us-west-2`
- Last option just use `json`
You can configure as many times as you want

## s3 Commands
1. `aws s3 ls s3://[bucket-name]`
   - Checks the latest contents in the bucket
2. `aws s3 cp [file-directory] s3://[bucket-name]`
   - Add one file to the bucket
4. `aws s3 cp [folder-directory] s3://[bucket-name] --recursive`
   - Add a whole folder to the bucket
6. `aws s3 sync [folder-directory] s3://[bucket-name]`
    - Add a whole folder to the bucket, and updates any changes made in that folder.
