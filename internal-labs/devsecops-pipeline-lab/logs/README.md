# 🔹 EDS DevSecOps Pipeline Lab — Logs Documentation

This directory stores log outputs related to the setup, operation, and troubleshooting of services deployed in the DevSecOps Pipeline Lab environment.

Logs are captured during installation processes, pipeline runs, container health checks, and security scans to support incident review and lab validation.

---

## 📊 Planned Logs to Capture

| Log Filename | Description |
|:---|:---|
| `jenkins-install-log.txt` | Output of Jenkins installation and initial configuration |
| `docker-container-status.log` | Status report of all containers after first deployment |
| `gitlab-runner-registration.log` | Logs from GitLab runner registration process |
| `pipeline-build-log.txt` | Sample build output from a full CI/CD pipeline run |
| `sonarqube-scan-results.log` | SonarQube static analysis scan results summary |

---

## 🔹 Log Capture Guidelines

- Save logs in plain text `.log` or `.txt` formats.
- Organize logs by service or pipeline stage when possible.
- Prefix filenames consistently: `service-name-purpose.log`
- Include timestamps inside the logs if supported.

---

## 🔒 Internal Use Only

All log files are for internal reference only and must not be shared externally without redaction and security validation.

Logs may contain sensitive system information.

---

> **Maintained by Eagle Defense Systems (EDS) Labs Team**

---
