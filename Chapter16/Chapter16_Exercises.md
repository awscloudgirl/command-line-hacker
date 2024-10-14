# Chapter 16: Exercises

## Exercise 1: Creating and Managing Cron Jobs

- **Objective**: Practice creating and managing cron jobs.
- **Tasks**:
  1. Use `crontab -e` to create a new cron job that runs a script every day at midnight.
  2. List all current cron jobs using `crontab -l` and verify your new job is listed.
  3. Modify the cron job to run every hour and observe the changes.

## Exercise 2: Configuring Anacron

- **Objective**: Learn to configure Anacron for periodic tasks.
- **Tasks**:
  1. Set up an Anacron job to run a maintenance script weekly.
  2. Verify the Anacron configuration in `/etc/anacrontab`.
  3. Test the Anacron job by simulating a missed execution and ensuring it runs at the next opportunity.

## Exercise 3: Using Systemd Timers

- **Objective**: Explore the use of systemd timers for task scheduling.
- **Tasks**:
  1. Create a systemd timer unit to run a backup script daily.
  2. Enable and start the timer using `systemctl`, and verify its status.
  3. Compare the functionality and flexibility of systemd timers with cron jobs.

## Exercise 4: Monitoring and Troubleshooting Scheduled Jobs

- **Objective**: Monitor and troubleshoot scheduled jobs.
- **Tasks**:
  1. Check the system logs for cron job execution results and identify any errors.
  2. Use `systemctl` to view the status and logs of a systemd timer.
  3. Document any issues encountered and the steps taken to resolve them.

## Exercise 5: Advanced Cron Job Scheduling

- **Objective**: Implement advanced scheduling techniques with cron.
- **Tasks**:
  1. Create a cron job that runs a script on the first Monday of every month.
  2. Set up a cron job with multiple schedules using a single entry.
  3. Experiment with environment variables in crontab to customize job execution.
