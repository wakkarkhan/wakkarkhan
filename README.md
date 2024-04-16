### Hi there 👋

<?php

namespace Wakkarkhan;

class About extends Me
{
    public function getBio(): string
    {
        return 'I m a software developer specializing in PHP and JavaScript.
                I develop modern technology web applications with popular frameworks like Laravel, Vue and React.
                SaaS,
                Multi-Tenancy,
                E-Commerce,
                RestFull API
                I develop advanced software with software architectures.
                Eternal student.';
    } 

    public function getMore(): array
    {
        return [
            'work' => [
                'Software Developer - Codematics',
                'Frontend Developer - Propertise',
            ]
        ];
    }

    public function getCurrentState(): array 
    {
        return [
            'working_on' => [
                'Propertise - Cloud-based property management software (SaaS)',
                'Ecommerce - Livewire eccomerce application'
            ],
            'learning' => [
                'Advance Programing Techniques',
                'Goo Lang'
            ]
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
