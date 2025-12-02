[<img alt="Super Mario Gif" width="100%" src="https://user-images.githubusercontent.com/70382532/138322189-2db8df52-9dcb-40a0-88a8-c365466bd33d.gif">](https://github.com/babisobrinho)
Art by <a href="https://www.instagram.com/pixeljeff_design">@pixeljeff_design</a>

##
<br/>

```php
<?php

namespace babiSobrinho;

class About extends Me
{
    public function getCurrentSituation(): array
    {
        return [
            'openToWork' => [
                'type' => 'Freelancing',
                'position' => 'Full-stack Web Developer',
                'availability' => 'Available for new projects'
            ],
            'languages' => [
                'Portuguese' => 'Native',
                'English' => 'C1',
                'French' => 'C1',
                'Spanish' => 'A1'
            ]
        ];
    }

    public function getEducation(): array
    {
        return [
            'latest_education' => [
                'institution' => 'IEFP Leiria',
                'course' => 'Technologies and Information Systems Programming',
                'period' => '2024-2025',
                'level' => 'EQF Level 5'
            ],
            'additional_education' => [
                [
                    'institution' => 'Instituto Politécnico de Leiria',
                    'course' => 'Web Development & Multimedia',
                    'period' => '2021-2023',
                    'level' => 'EQF Level 5'
                ],
                [
                    'institution' => 'Batalha High School',
                    'course' => 'Computer Systems Management and Programming',
                    'period' => '2015-2018',
                    'level' => 'EQF Level 4'
                ]
            ]
        ];
    }

    public function getCertifications(): array
    {
        return [
            [
                'title' => 'Agile Management: Exploring Agility Concepts',
                'issuer' => 'Alura - Online Technology Courses',
                'date' => 'May 2024'
            ],
            [
                'title' => 'Initial Pedagogical Training for Trainers',
                'issuer' => 'Instituto do Emprego e Formação Profissional',
                'date' => 'November - December 2023'
            ],
            [
                'title' => 'Roadmap: How to Create and Maintain the Product Map',
                'issuer' => 'Alura - Online Technology Courses',
                'date' => 'October 2023'
            ],
            [
                'title' => 'Culture and Agile Methods: Pillars for Advanced Immersion',
                'issuer' => 'Alura - Online Technology Courses',
                'date' => 'October 2023'
            ],
            [
                'title' => 'Tools for Agility: Overview of Project and Product Control',
                'issuer' => 'Alura - Online Technology Courses',
                'date' => 'October 2023'
            ]
        ];
    }

    public function getExperience(): array
    {
        return [
            'current' => [
                'position' => 'Full-stack Web Developer',
                'company' => 'Latitude - Digital Enablers, Lda',
                'type' => 'Internship | Hybrid',
                'period' => 'July - October 2025 / March - July 2023',
                'location' => 'Lisboa, Portugal',
                'achievements' => [
                    'Collaborated directly with national and international clients',
                    'Developed full-stack web pages from Figma mockups',
                    'Implemented backend features using Laravel',
                    'Built Role-Based Access Control (RBAC) system with Spatie'
                ],
                'technologies' => [
                    'Laravel', 'PHP', 'TailwindCSS', 'Bootstrap', 'JS', 'JQuery',
                    'Ajax', 'Livewire', 'AlpineJS', 'PostgreSQL', 'Spatie',
                    'MariaDB', 'RESTful API', 'GitHub', 'Docker', 'Azure'
                ]
            ],
            'freelance_experience' => [
                [
                    'period' => 'October 2023 - November 2024',
                    'location' => 'Leiria, Portugal (Remote)',
                    'projects' => [
                        'ERP system for condominium management',
                        'Custom CMS for web design company',
                        'Architect portfolio website with custom backoffice',
                        'WordPress migration for Jornal de Leiria',
                        'Led 3-person team for LMS platform implementation'
                    ],
                    'methodologies' => ['Agile', 'Scrum'],
                    'technologies' => [
                        'Laravel', 'PHP', 'TailwindCSS', 'Bootstrap', 'JavaScript',
                        'JQuery', 'Ajax', 'AlpineJS', 'MariaDB', 'MySQL', 'Spatie',
                        'DataTables', 'Python', 'WordPress', 'GitHub', 'Jira', 'Confluence'
                    ]
                ],
                [
                    'period' => 'March - September 2021',
                    'location' => 'Leiria, Portugal (Remote)',
                    'projects' => [
                        'Hugo websites for events',
                        'Kirby website maintenance and enhancements',
                        'Website rebranding initiatives'
                    ],
                    'technologies' => [
                        'Laravel', 'PHP', 'TailwindCSS', 'JavaScript', 'AlpineJS',
                        'JQuery', 'Ajax', 'MySQL', 'Kirby', 'Hugo', 'Golang'
                    ]
                ],
                [
                    'period' => 'February - April 2018 / June - August 2017',
                    'company' => 'Movicortes - Serviços e Gestão S.A.',
                    'type' => 'Internship | On-site',
                    'location' => 'Leiria, Portugal',
                    'achievements' => [
                        'Led migration of internal sales team website to Joomla'
                    ],
                    'technologies' => ['Joomla', 'PHP', 'HTML', 'CSS', 'Bootstrap', 'JavaScript']
                ]
            ]
        ];
    }

    public function getSkills(): array
    {
        return [
            'soft_skills' => [
                'Proactive', 'Responsible', 'Teamwork', 'Adaptable',
                'Fast Learner', 'Problem-Solving', 'Decision-Making',
                'Resilient', 'Good Communication', 'Facilitation', 'Open-Minded'
            ],
            'programming' => [
                'frontend' => ['HTML', 'CSS', 'Bootstrap', 'TailwindCSS', 'JavaScript', 'AlpineJS', 'JQuery', 'Ajax'],
                'backend' => ['PHP', 'Laravel', 'MySQL', 'Python', 'Go', 'C', 'C++', 'ASP.NET'],
                'cms' => ['WordPress', 'Joomla', 'Kirby', 'Hugo'],
                'mobile' => ['Kotlin', 'Swift']
            ],
            'project_management' => ['Azure DevOps', 'Jira', 'Confluence', 'Trello', 'Agile Methodologies'],
            'tools' => [
                'development' => ['Laragon', 'XAMPP', 'VS Code', 'PhpStorm', 'GitHub', 'GitLab', 'Postman'],
                'design' => ['Figma', 'Zeplin', 'Adobe Xd', 'Adobe Photoshop', 'Canva', 'CorelDRAW'],
                'mobile_dev' => ['Android Studio', 'IntelliJ IDEA', 'Swift Playground']
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Javascript::class,
            Bootstrap::class,
            TailwindCss::class,
            AlpineJs::class,
            MySql::class,
            Git::class,
            AgileMethodologies::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source while building impactful full-stack solutions.';
    }
}
```

<!-- Contact Links -->
[<img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=E64DA1" target="_blank"/>](https://www.linkedin.com/in/babisobrinho)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/babisobrinho/babisobrinho/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/babisobrinho/babisobrinho/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/babisobrinho/babisobrinho/output/github-contribution-grid-snake.svg">
</picture>
