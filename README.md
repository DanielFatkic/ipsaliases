# ipsaliases

A small tool to generate class aliases for Invision Community Suite files.

Installation via composer:
`composer require danielfatkic/ipsaliases`

Then call  `vendor/bin/generatealiases .` to generate the alias file which will look like:

```
<?php 
class_alias(IPS\forums\_Application::class, 'IPS\forums\Application', false);
class_alias(IPS\forums\tasks\_archive::class, 'IPS\forums\tasks\archive', false);
...
