# change-asg-elb-endpoint

Change the ASG ELB endpoint, it will return the name of the old ASG as `old_asg_name`

## Role Variables

* `asg`      : Dictionary storing information of the Auto Scaling Group
  * `name`   : Auto Scaling Group name
* `elb`      : Dictionary storing information of the Elastic Load Balancer
  * `name`   : Elastic Load Balancer name
  * `region` : Elastic Load Balancer region

## Example playbook

```yaml
- hosts: localhost
  connection   : local
  gather_facts : no
  roles:
    - change-asg-elb-endpoint
```

## License

GPLv2

## Author Information
jamatute (jamatute@paradigma)
