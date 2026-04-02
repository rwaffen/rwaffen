## The Motto

"We the willing, led by the ignorant, do the impossible for the ungrateful. We have accomplished so much with so little for so long that we are now able to do anything with nothing!"

~ Alexander Sergejewitsch Puschkin

"Make it work, make it right, make it fast!"

~ Kent Beck

## The Basics

```puppet
person { 'Robert Waffen':
  job_title     => 'Señor Agile Enterprise DevOps',
  home          => '/home/Leipzig',
}

contact { 'How_to_contact_me':
  ensure    => 'digital',
  phone     => '<Redacted>',
  mail      => '<Redacted>',
  github    => '@rwaffen',
  mastodon  => '@rwaffen@fosstodon.org'
  require   => Person['Robert Waffen'],
}
```

## The Details

```ruby
Operating_Systems   = [ "RedHat", "CentOS", "Ubuntu", "macOS" ]
Automation          = [ "Puppet", "Ansible", "Terraform" ]
Monitoring          = [ "Icinga2", "Prometheus", "ELK Stack" ]
Programming         = [ "Ruby", "Bash", "Python" ]
Server_Applications = [ "Apache", "Nginx", "Tomcat" ]
Cloud               = [ "AWS", "GCP", "Hetzner"]
Virtualization      = [ "VMWare", "KVM", "Docker", "Container", "K8S" ]
Databases           = [ "MySQL", "Oracle Database", "Elasticsearch" ]
```
