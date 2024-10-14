# Chapter 11: Exercises

## Exercise 1: Exploring System Logs

- **Objective**: Familiarize yourself with common system log files.
- **Tasks**:
  1. Use `cat` or `less` to view the contents of `/var/log/syslog` or `/var/log/messages`.
  2. Identify and describe the types of messages found in `/var/log/auth.log`.
  3. Explore other log files in `/var/log` and note their purposes.

## Exercise 2: Using journalctl

- **Objective**: Practice using `journalctl` to query systemd logs.
- **Tasks**:
  1. Use `journalctl` to display the most recent log entries.
  2. Filter log entries by a specific service, such as `sshd`.
  3. Use `journalctl` to view logs from a specific boot session.

## Exercise 3: Configuring Logrotate

- **Objective**: Learn to manage log rotation with `logrotate`.
- **Tasks**:
  1. Review the configuration file for `logrotate` located in `/etc/logrotate.conf`.
  2. Create a custom logrotate configuration for a specific log file.
  3. Test the log rotation manually and verify the results.

## Exercise 4: Custom Logging Configuration

- **Objective**: Set up custom logging for an application.
- **Tasks**:
  1. Configure a simple application to log messages to a custom log file.
  2. Set different log levels (e.g., error, warning, info) and observe the output.
  3. Redirect log output to a remote syslog server (if applicable).

## Exercise 5: Analyzing Log Data

- **Objective**: Analyze log data to identify issues or patterns.
- **Tasks**:
  1. Use `grep` to search for specific error messages in a log file.
  2. Analyze log entries to identify patterns or recurring issues.
  3. Create a summary report of significant events from the logs.
