# Contributing to StratumCMS

Thanks for taking the time to contribute!  
This org hosts the **core CMS**, official **modules**, and **themes**.

## 📖 Read the Documentation First
Our documentation contains the full guide for:
- Installing and running StratumCMS
- Creating and publishing **modules**
- Creating and publishing **themes**
- Coding standards, hooks, and extension points

➡️ **Start here**: [StratumCMS Documentation – Contributing](https://stratumcms.com/documentation)

## Repositories
- Core CMS: https://github.com/StratumCMS/Stratum
- Modules: `StratumCMS/module-<slug>`
- Themes:  `StratumCMS/theme-<slug>`

## Development requirements
- PHP 8.2+
- Composer 2.x
- Node.js (for theme/front-end builds)
- Laravel 11
- Pest, PHPStan, Laravel Pint

## Coding standards
- **PSR-12** with **Laravel Pint**
- **PHPStan** (level 6/7)
- **Pest** tests; new features should be covered
- **Conventional Commits** (`feat:`, `fix:`, `docs:`, `refactor:`, `test:`, `chore:`)
- **SemVer** for releases

## Pull requests
1. Create a branch: `features/<slug>` or `fix/<slug>`
2. Run: `composer lint && composer stan && composer test`
3. Update docs if needed (see link above)
4. Open a PR; CI must pass; **1 review** minimum

## Issues & labels
Use labels: `bug`, `feature`, `docs`, `good first issue`, `help wanted`, `security`.

## Security
Please **do not** open public issues for vulnerabilities.  
See [SECURITY](SECURITY.md) for how to report them privately.

## License
By contributing, you agree that your contributions are licensed under the [MIT License](LICENSE).
