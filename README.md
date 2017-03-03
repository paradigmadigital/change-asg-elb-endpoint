# change-asg-elb-endpoint

Change the ASG ELB endpoint

## Role Variables

* `asg.name`                    : Auto Scaling Group name
* `elb.name`                    : Elastic Load Balancer name

## Example playbook

```yaml
- hosts: localhost
  connection: local
  gather_facts: no
  roles:
    - change-asg-elb-endpoint
```

## License

GPLv2

## Author Information
jamatute (jamatute@paradigma)
