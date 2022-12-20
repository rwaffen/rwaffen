## The Basics

```
person { 'Robert Waffen':
  job_title    => 'Agile Enterprise DevOps',
  home         => '/home/Berlin',
  age          => 37,
}
-> contact { 'How_to_contact_me':
  ensure    => 'digital',
  phone     => '<Redacted>',
  mail      => '<Redacted>',
  twitter   => '@rand0m_rob',
  gitlab    => '@rwaffen',
  fediverse => '@rand0mbytes@social.rand0m.fail',
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
