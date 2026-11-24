# Lab 01 — Linux Fundamentals & Service Troubleshooting

**Status:** In progress  
**Environment:** Disposable Fedora Server VM managed with Vagrant and VMware Workstation.

## Objective

Practice Linux administration through a realistic service outage. The learner receives an incident ticket, gathers evidence, identifies the root cause, applies a controlled fix, and verifies recovery.

## Learning topics

- Linux processes and PIDs.
- Signals and graceful process termination.
- systemd units and service lifecycle.
- File ownership and permissions.
- Service logs with journalctl.
- Listening sockets and application health checks.
- Evidence-based troubleshooting.

## Planned scenario

**Incident:** The DevOps Training Application is unavailable on TCP port 8080.

**Constraints:**
- Do not reboot the VM.
- Do not reinstall packages.
- Do not blindly restart services.
- Collect evidence before making changes.
- Record the exact root cause and verification steps.

The failure-injection script will be committed after the VMware Vagrant box and provider are validated on the host. Do not assume an unverified box name or provider configuration.

## Lab lifecycle

The intended workflow is:

```powershell
vagrant up --provider=vmware_desktop
vagrant ssh
vagrant status
vagrant halt
vagrant destroy -f
```

## Deliverables

- Vagrantfile and provisioning scripts.
- Incident scenario and constraints.
- Troubleshooting evidence.
- Root-cause analysis and remediation.
- Lessons learned.

## Evidence

See the `evidence/` directory for the incident report template.
