# Linux System Log Monitoring Notes

## Objective
The purpose of this practical was to understand Linux system log monitoring, log analysis, and troubleshooting using common Linux commands.

# Commands Learned
## 1. journal
Used to view logs collected by systemd.
### Purpose
- View complete system logs
- Analyze system events
- Monitor services and boot logs

## 2. tail
Used to display the last lines of a file.
### Purpose
- Monitor logs in real time
- View latest log entries

## 3. head
Used to display the first lines of a file.
### Purpose
- Quickly preview log files
- Check beginning entries

## 4. wc
Used to count:
- lines
- words
- characters

### Purpose
- Analyze file size and content count

## 5. cat
Used to display file contents.
### Purpose
- Read complete file contents

## 6. grep
Used to search specific text patterns inside files.
### Purpose
- Search logs for error messages
- Filter important information

## 7. Authentication Logs
### Purpose
- View login and authentication activity
- Monitor sudo usage and login attempts

# Linux Log Files Learned
| Log File | Purpose |
|---|---|
| /var/log/syslog | General system logs |
| /var/log/auth.log | Authentication logs |
| journal logs | systemd logs |

# Skills Practiced
- Linux system monitoring
- Real-time log analysis
- Troubleshooting
- Searching logs
- Viewing authentication logs
- Command-line usage

# Challenges Faced
- Understanding large log outputs
- Identifying useful entries
- Learning command syntax
- Monitoring logs in real time

# Learning Outcome
This practical improved my understanding of Linux monitoring, troubleshooting, and basic security-focused log analysis techniques used in cyber security and system administration.

# Important Commands Summary
sudo journal
tail /var/log/syslog
head /var/log/syslog
wc /var/log/syslog
cat /var/log/syslog
cat term.log | grep "error"
sudo cat /var/log/auth.log

# Conclusion
This practical provided hands-on experience with Linux log monitoring and helped improve understanding of system activity, authentication logs, and troubleshooting techniques.
