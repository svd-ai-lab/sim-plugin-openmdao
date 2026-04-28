# sim-plugin-openmdao

OpenMDAO driver for [sim-cli](https://github.com/svd-ai-lab/sim-cli),
distributed as an out-of-tree plugin.

OpenMDAO driver for sim.

## Install

```bash
sim plugin install openmdao
```

Other paths:

```bash
pip install git+https://github.com/svd-ai-lab/sim-plugin-openmdao@v0.1.0
pip install https://github.com/svd-ai-lab/sim-plugin-openmdao/releases/download/v0.1.0/sim_plugin_openmdao-0.1.0-py3-none-any.whl
pip install -e .
```

After install:

```bash
sim plugin doctor openmdao
sim plugin sync-skills
```

## Development

```bash
git clone https://github.com/svd-ai-lab/sim-plugin-openmdao
cd sim-plugin-openmdao
uv sync
uv run pytest
```

## License

Apache-2.0.
