```php
<?php

namespace Balat/Readme;

class TYPO3Developer
{
  protected $description = [
    'name' => 'Dragan Balatinac',
    'role' => 'TYPO3 Developer',
    'location' => 'Essen, Germany',
    'technologies' => 'TYPO3, Fluid, Extbase, PHP, 
      MySQL, Linux, Laravel, Symfony, JavaScript',
    'email' => 'dragan@balatinac.com' 
  ];
  
  public function getDescription()
  {
    return $this->description;
  }
}
```
