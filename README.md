## The Basics

```
person { 'Robert Waffen':
  job_title    => 'Agile Enterprise DevOps',
  home         => '/home/Berlin/Lichtenberg',
  age          => 36,
  relationship => undef,
}
-> contact { 'How_to_contact_me':
  ensure  => 'digital',
  phone   => '<Redacted>',
  mail    => '<Redacted>',
  twitter => '@zero0ne',
  gitlab  => '@rwaffen',
}
```

## The Details

```
Operating_Systems   = [ "RedHat", "CentOS", "Ubuntu", "macOS" ]
Automation          = [ "Puppet", "Ansible", "Terraform" ]
Monitoring          = [ "Icinga2", "Prometheus", "ELK Stack" ]
Programming         = [ "Ruby", "Bash", "Python", "PHP" ]
Server_Applications = [ "Apache", "Nginx", "Tomcat" ]
Cloud               = [ "AWS", "GCP", "DigitalOcean", "Hetzner"]
Virtualization      = [ "VMWare", "KVM" ]
Databases           = [ "MySQL", "Oracle Database", "Elasticsearch" ]
```
