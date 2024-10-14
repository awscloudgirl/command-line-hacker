# Chapter 12: Exercises

## Exercise 1: Managing Services with systemctl

- **Objective**: Practice managing services using `systemctl`.
- **Tasks**:
  1. Use `systemctl` to start and stop a service, such as `nginx` or `apache2`.
  2. Check the status of a service and interpret the output.
  3. Enable a service to start automatically at boot and verify the configuration.

## Exercise 2: Configuring Service Files

- **Objective**: Learn to configure service settings.
- **Tasks**:
  1. Locate the configuration file for a service, such as `sshd`, in `/etc`.
  2. Modify a configuration setting, such as the port number, and restart the service.
  3. Verify that the changes have taken effect by checking the service status.

## Exercise 3: Securing Services

- **Objective**: Implement security measures for services.
- **Tasks**:
  1. Configure a firewall rule to allow traffic only to a specific service port.
  2. Set up access controls to restrict which users can start or stop a service.
  3. Review and apply security best practices for a commonly used service.

## Exercise 4: Understanding Systemd and Init Systems

- **Objective**: Explore the role of systemd in service management.
- **Tasks**:
  1. List all active services managed by systemd using `systemctl list-units`.
  2. Examine the dependencies of a service using `systemctl list-dependencies`.
  3. Create a simple systemd service file and test its functionality.

## Exercise 5: Monitoring and Logging Services

- **Objective**: Monitor service performance and analyze logs.
- **Tasks**:
  1. Use `journalctl` to view logs for a specific service and identify any errors.
  2. Monitor the resource usage of a service using `top` or `htop`.
  3. Create a report summarizing the performance and any issues found in the logs.
