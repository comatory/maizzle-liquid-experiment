<div align="center">
  <p>
    <a href="https://maizzle.com" target="_blank">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github.com/maizzle/maizzle/raw/master/.github/logo-dark.svg">
        <img alt="Maizzle Starter" src="https://github.com/maizzle/maizzle/raw/master/.github/logo-light.svg" width="300" height="225" style="max-width: 100%;">
      </picture>
    </a>
  </p>

  **LiquidJS starter**
</div>

## The problem

The template at `./emails/transactional.html` uses `defaultImageUrl` data that we need to render literally. However the URL following `default:` ends up being rendered with `&quot;` instead of `"`.

1. Clone the repo
2. Run `npm install`
3. Run `npm run build`
4. Look at output in `./build_production/emails/transactional.html`, and check the URL following `default:`

## Getting Started

This starter shows how to use [LiquidJS](https://liquidjs.com/) with Maizzle.

```bash
npx create-maizzle
```

When prompted to select a Starter, choose **Custom ➜ Liquid**.

## Documentation

Maizzle documentation is available at https://maizzle.com

## Issues

Please open all issues in the [framework repository](https://github.com/maizzle/framework).

## License

The Maizzle framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

[npm]: https://www.npmjs.com/package/@maizzle/framework
[npm-stats]: https://npm-stat.com/charts.html?package=%40maizzle%2Fframework&from=2019-03-27
[npm-version-shield]: https://img.shields.io/npm/v/@maizzle/framework.svg
[npm-stats-shield]: https://img.shields.io/npm/dt/@maizzle/framework.svg?color=6875f5
[github-ci]: https://github.com/maizzle/framework/actions
[github-ci-shield]: https://github.com/maizzle/framework/actions/workflows/nodejs.yml/badge.svg
[license]: ./LICENSE
[license-shield]: https://img.shields.io/npm/l/@maizzle/framework.svg?color=0e9f6e
