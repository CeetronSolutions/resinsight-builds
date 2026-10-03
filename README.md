# ResInsight Builds

This repository distributes automated **dev** builds of
[OPM/ResInsight](https://github.com/OPM/ResInsight).

It holds no source code. A rolling pre-release named `dev-latest` is
published here by the `publish-dev-build` CI job in
[`ResInsightWithCache.yml`](https://github.com/OPM/ResInsight/blob/dev/.github/workflows/ResInsightWithCache.yml),
giving users a permanent, unauthenticated download URL for the latest `dev`
branch build of each supported platform, served by GitHub's CDN.

See [`docs/ci-dev-builds-setup.md`](https://github.com/OPM/ResInsight/blob/dev/docs/ci-dev-builds-setup.md)
in the ResInsight repository for details on how the publishing job works.

## Downloads

Latest `dev` build assets are available on the
[`dev-latest` release](https://github.com/CeetronSolutions/resinsight-builds/releases/tag/dev-latest).

⚠️ These are automated builds from the `dev` branch and may be unstable.
For stable releases, see the
[OPM/ResInsight releases](https://github.com/OPM/ResInsight/releases) page.
