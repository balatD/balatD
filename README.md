```php
<?php

declare(strict_types=1);

namespace Balat\Readme;

final readonly class DraganBalatinac
{
    public string $role;
    public string $location;

    public function __construct()
    {
        $this->role = 'Teamlead Backend Development';
        $this->location = 'Essen, Germany';
    }

    public function worksWith(): array
    {
        return [
            'TYPO3' => ['Fluid', 'Extbase'],
            'PHP' => ['Laravel', 'Symfony'],
            'Frontend' => ['JavaScript', 'TypeScript', 'React', 'Inertia', 'NextJS'],
            'Data' => ['MySQL', 'PostreSQL', 'Redis'],
            'Infrastructure' => ['Linux', 'Docker', 'Ansible'],
            'CMS' => ['Payload CMS', 'Statamic'],
        ];
    }

    public function caresAbout(): array
    {
        return [
            'clean code',
            'scalable architecture',
            'great developer experience',
            'knowledge sharing',
        ];
    }

    public function sayHello(): string
    {
        return 'Let’s build something great.';
    }

    public function contact(): string
    {
        return 'dragan@balatinac.com';
    }
}
```
