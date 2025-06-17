# README - Onboarding for PARNET projects

## TODOs


- [ ] Finish notebooks
- [ ] Complete README
- [ ] Provide with more instructions about set-up

## Set-up instructions

### Datasets

Store (or symlink) the provided datasets into the `resources/` directory. The expected structure is as follows:

```bash
./resources/
├── general/
├── parnet_encore_eclip/
├── parnet_models/
└── sun_et_al_2021_icshape_data/
```

### Virtual environment

```bash
pixi install -e "parnet-demo"
pixi install -e "parnet-gpu-demo"
```

## Demo

