# Prerequisite

1. Start with a fresh account in AWS.
2. Create a user named `admin` in IAM Console.
3. Generate and save the Access Key ID and Secret Access Key of this user.
4. Assign AdministratorAccess policy to this user.

# Create Developer Account

```shell
# Create the user
aws iam create-user --user-name developer

# Create a secret key, and save the Access Key ID and Secret Access Key
aws iam create-access-key --user-name developer


```

# Create Auditor Account

```shell
# Create the user
aws iam create-user --user-name auditor

# Create a secret key, and save the Access Key ID and Secret Access Key
aws iam create-access-key --user-name auditor
```
