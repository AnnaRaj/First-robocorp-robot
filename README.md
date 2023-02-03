# Template: Standard Robot Framework

This is the simplest template to start from.

- Get started from a simple task template in `tasks.robot`.
  - Uses [Robot Framework](https://robocorp.com/docs/languages-and-frameworks/robot-framework/basics) syntax.
- You can configure your robot `robot.yaml`.
- You can configure dependencies in `conda.yaml`.

## Learning materials

- [Robocorp Developer Training Courses](https://robocorp.com/docs/courses)
- [Documentation links on Robot Framework](https://robocorp.com/docs/languages-and-frameworks/robot-framework)
- [Example bots in Robocorp Portal](https://robocorp.com/portal)


Remove the hard-coded login credentials from the robot to a vault for better security.

To test this, create vault.json file in your home directory (/Users/<username>). Paste the following JSON and update the value for the username and the password properties:

{
  "robotsparebin": {
    "username": "username-here",
    "password": "password-here"
  }
}
Upadate the path to the vault.json file in the devdata/json file.