<p align="center">
  <a href="https://bios-webapp.vercel.app/demonstracao"><img src="assets/banner.en.png" width="100%" alt="BIOS: company sustainability, evidence by evidence. From the CNPJ to the adherence index for SDGs 13 and 15, with every point traceable to the official source."></a>
</p>

<p align="center">
  🇧🇷 <a href="README.md">Português</a> · 🇺🇸 <strong>English</strong>
</p>

<p align="center">
  <a href="https://bios-webapp.vercel.app/demonstracao"><img src="https://img.shields.io/badge/Open_the_demo-2c5f2d?style=for-the-badge" alt="Open the demo"></a>
</p>

# BIOS — Business Intelligence on Sustainability

BIOS uses the CNPJ, the Brazilian company registry number, as the axis to gather public environmental
evidence about Brazilian companies and to explain, evidence by evidence, how each one adheres to SDGs
13 (climate action) and 15 (life on land). The index always comes with a confidence level and a path
back to the official source.

> **Evidence First:** no index exists without traceable evidence, and missing data lowers the
> confidence, never the index.

## See it working

<table>
  <tr>
    <td width="66%" valign="middle"><a href="https://bios-webapp.vercel.app/demonstracao"><img src="assets/demo.webp" width="100%" alt="Demo: lookup by CNPJ, company evidence, index explanation and sector search"></a></td>
    <td width="34%" valign="middle" align="center"><a href="https://bios-webapp.vercel.app/demonstracao"><img src="assets/qr.en.png" width="100%" alt="QR Code that opens BIOS with the demo account already signed in"></a></td>
  </tr>
</table>

The demo opens right away, with no sign-up, and runs in the browser on static files generated from
real public data. The account is fictional, and nothing you do there leaves your tab. The interface
is in Portuguese.

## The three repositories

<p align="center">
  <a href="https://github.com/odavibatista/bios-webapp"><img src="assets/card-web.en.png" width="32%" alt="bios-webapp: lookup, index explanation, search and evolution by sector. Angular, Material 3 and Playwright."></a>
  <a href="https://github.com/odavibatista/bios-core-api"><img src="assets/card-api.en.png" width="32%" alt="bios-core-api: public source collection, evidence, indices and a documented API. NestJS, MongoDB and BullMQ."></a>
  <a href="https://github.com/odavibatista/bios-docs"><img src="assets/card-docs.en.png" width="32%" alt="bios-docs: requirements, use cases, modeling and environmental impact. ISO 29148, ISO 25010 and C4."></a>
</p>

<p align="center">
  <img src="assets/numbers.en.png" width="100%" alt="110,372 companies in the demo, 580,166 public evidence records, 34 functional requirements, 3,934 unit tests, 1,162 e2e tests and 99.71% of lines covered in the API">
</p>

## How the parts connect

<p align="center">
  <img src="assets/ecosystem.en.png" width="100%" alt="Public sources feed bios-core-api, which serves bios-webapp and third-party systems; bios-docs defines the requirements of both">
</p>

## Where to start

| If you want to see                            | Go to                                                          |
| :-------------------------------------------- | :------------------------------------------------------------- |
| The product in use                            | [Demo](https://bios-webapp.vercel.app/demonstracao)            |
| Interface, accessibility and end-to-end tests | [bios-webapp](https://github.com/odavibatista/bios-webapp)     |
| Data collection, index rules and API contract | [bios-core-api](https://github.com/odavibatista/bios-core-api) |
| Requirements, traceability and method         | [bios-docs](https://github.com/odavibatista/bios-docs)         |

## Privacy and data removal

BIOS works with public data linked to the CNPJ. A sole proprietor's registered name and address may
contain the owner's personal data, even though they are public at the Federal Revenue Service. A CPF
in the registered name is masked, and partners and contacts are not collected.

To request the removal of a record, write to **odavibatista@hotmail.com** with the CNPJ and proof that
you are the owner. The details are on the
[privacy page](https://bios-webapp.vercel.app/privacidade).

## Author

A project by **Davi Deosmar Batista Oliveira Miranda**, from São Paulo, for the Computer Science
program at Universidade São Judas Tadeu (USJT), in the Software Engineering and Software Management
and Quality courses.

<p>
  <a href="https://www.linkedin.com/in/odavibatista/"><img src="https://img.shields.io/badge/LinkedIn-2c5f2d?style=flat-square" alt="LinkedIn"></a>
  <a href="https://github.com/odavibatista"><img src="https://img.shields.io/badge/GitHub-2c5f2d?style=flat-square" alt="GitHub"></a>
</p>

## License

All rights reserved. The repositories are public for reference and academic assessment; see
[LICENSE](LICENSE).
