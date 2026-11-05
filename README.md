<p align="center">
  <a href="https://bios-webapp.vercel.app/demonstracao"><img src="assets/banner.pt.png" width="100%" alt="BIOS: sustentabilidade de empresas, evidência por evidência. Do CNPJ ao índice de aderência aos ODS 13 e 15, com cada ponto rastreável até a fonte oficial."></a>
</p>

<p align="center">
  🇧🇷 <strong>Português</strong> · 🇺🇸 <a href="README.en.md">English</a>
</p>

<p align="center">
  <a href="https://bios-webapp.vercel.app/demonstracao"><img src="https://img.shields.io/badge/Abrir_a_demonstra%C3%A7%C3%A3o-2c5f2d?style=for-the-badge" alt="Abrir a demonstração"></a>
</p>

# BIOS — Business Intelligence on Sustainability

O BIOS usa o CNPJ como eixo para reunir evidências ambientais públicas de empresas brasileiras e
explicar, evidência por evidência, a aderência de cada uma aos ODS 13 (ação climática) e 15 (vida
terrestre). O índice vem sempre com um nível de confiança e com o caminho até a fonte oficial.

> **Evidence First:** nenhum índice existe sem evidência rastreável, e a ausência de dado reduz a
> confiança, nunca o índice.

## Veja funcionando

<table>
  <tr>
    <td width="66%" valign="middle"><a href="https://bios-webapp.vercel.app/demonstracao"><img src="assets/demo.webp" width="100%" alt="Demonstração: consulta por CNPJ, evidências da empresa, explicação do índice e pesquisa por setor"></a></td>
    <td width="34%" valign="middle" align="center"><a href="https://bios-webapp.vercel.app/demonstracao"><img src="assets/qr.pt.png" width="100%" alt="QR Code que abre o BIOS já com a conta de demonstração"></a></td>
  </tr>
</table>

A demonstração abre direto, sem cadastro, e roda no navegador sobre arquivos estáticos gerados com
dados públicos reais. A conta é fictícia e nada do que você fizer ali sai da sua aba.

## Os três repositórios

<p align="center">
  <a href="https://github.com/odavibatista/bios-webapp"><img src="assets/card-web.pt.png" width="32%" alt="bios-webapp: consulta, explicação do índice, pesquisa e evolução por setor. Angular, Material 3 e Playwright."></a>
  <a href="https://github.com/odavibatista/bios-core-api"><img src="assets/card-api.pt.png" width="32%" alt="bios-core-api: coleta de fontes públicas, evidências, índices e API documentada. NestJS, MongoDB e BullMQ."></a>
  <a href="https://github.com/odavibatista/bios-docs"><img src="assets/card-docs.pt.png" width="32%" alt="bios-docs: requisitos, casos de uso, modelagem e impacto ambiental. ISO 29148, ISO 25010 e C4."></a>
</p>

<p align="center">
  <img src="assets/numbers.pt.png" width="100%" alt="110.372 empresas na demonstração, 580.166 evidências públicas, 34 requisitos funcionais, 3.934 testes unitários, 1.162 testes e2e e 99,71% de linhas cobertas na API">
</p>

## Como as partes se ligam

<p align="center">
  <img src="assets/ecosystem.pt.png" width="100%" alt="Fontes públicas alimentam o bios-core-api, que atende o bios-webapp e sistemas de terceiros; o bios-docs define os requisitos dos dois">
</p>

## Por onde começar

| Se você quer ver                                    | Vá para                                                        |
| :-------------------------------------------------- | :------------------------------------------------------------- |
| O produto em uso                                    | [Demonstração](https://bios-webapp.vercel.app/demonstracao)    |
| Interface, acessibilidade e testes de ponta a ponta | [bios-webapp](https://github.com/odavibatista/bios-webapp)     |
| Coleta de dados, regras do índice e contrato da API | [bios-core-api](https://github.com/odavibatista/bios-core-api) |
| Requisitos, rastreabilidade e método                | [bios-docs](https://github.com/odavibatista/bios-docs)         |

## Privacidade e remoção de dados

O BIOS trabalha com dados públicos ligados ao CNPJ. A razão social e o endereço de um empresário
individual podem conter dados pessoais do titular, mesmo sendo públicos na Receita Federal. O CPF na
razão social é mascarado, e sócios e contatos não são coletados.

Para pedir a remoção de um cadastro, escreva para **odavibatista@hotmail.com** com o CNPJ e uma
comprovação de que você é o titular. Os detalhes estão na
[página de privacidade](https://bios-webapp.vercel.app/privacidade).

## Autor

Projeto de **Davi Deosmar Batista Oliveira Miranda**, de São Paulo, no curso de Ciência da Computação
da Universidade São Judas Tadeu (USJT), para as disciplinas de Engenharia de Software e de Gestão e
Qualidade de Software.

<p>
  <a href="https://www.linkedin.com/in/odavibatista/"><img src="https://img.shields.io/badge/LinkedIn-2c5f2d?style=flat-square" alt="LinkedIn"></a>
  <a href="https://github.com/odavibatista"><img src="https://img.shields.io/badge/GitHub-2c5f2d?style=flat-square" alt="GitHub"></a>
</p>

## Licença

Todos os direitos reservados. Os repositórios são públicos para consulta e avaliação acadêmica; veja
[LICENSE](LICENSE).
