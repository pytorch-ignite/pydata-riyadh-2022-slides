# PyData Riyadh Mentored Sprint 2022/01/14 - PyTorch-Ignite slides

[Link to slides](https://pytorch-ignite.github.io/pydata-riyadh-2022-slides/)

## License

This repo is under the [MIT License](LICENSE).


## Instructions for Building Slides

0. Clone the repository with `--recursive` option:
```bash
git clone --recursive https://github.com/pytorch-ignite/pydata-global2021-slides.git
# or
# git submodule --init --recursive update
```

1. Install [hugo](https://gohugo.io/getting-started/installing/)

2. For development:

```bash
hugo server
```

3. In `config.toml` set `baseURL` to be the baseURL of your hosted website.

4. (Optional) In `config.toml` set `useMath = false` if there is not any math in your
slides.

## Acknowledgements

- This slides are highly inspired from Thomas' repository: https://github.com/thomasjpfan/slides-template-hugo . Thanks, Thomas !
