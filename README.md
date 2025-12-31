# Arizona Rules in Akoma Ntoso XML

This repository contains Arizona statutes and regulations encoded in [Akoma Ntoso](http://www.akomantoso.org/) XML format for machine-readable legal analysis.

## Structure

```
rules-us-az/
├── statutes/                    # Arizona Revised Statutes (A.R.S.)
│   ├── title-42-taxation/       # Title 42 - Taxation
│   └── title-46-welfare/        # Title 46 - Welfare
└── regulations/                 # Arizona Administrative Code (A.A.C.)
```

## Sources

- **Arizona Revised Statutes**: https://www.azleg.gov/arsDetail/
- **Arizona Administrative Code**: https://apps.azsos.gov/public_services/Title_Search/

## Akoma Ntoso Format

All documents follow the [Akoma Ntoso 3.0](http://docs.oasis-open.org/legaldocml/akn-core/v1.0/akn-core-v1.0.html) standard for legal documents. Key elements:

- `<act>` - Primary legislation (statutes)
- `<doc>` - Regulatory documents
- `<article>` - Individual sections
- `<paragraph>` - Subsections

## Related Repositories

- [CosilicoAI/arch](https://github.com/CosilicoAI/arch) - Source document archive
- [CosilicoAI/rac](https://github.com/CosilicoAI/rac) - Rules as Code DSL

## License

Source legal text is public domain. Repository structure and tooling are MIT licensed.
