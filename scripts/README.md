```bash
huggingface-cli download --resume-download google/siglip-so400m-patch14-384 --local-dir siglip-so400m-patch14-384
```


```bash
python -m eval_sim.eval_rdt_maniskill \
    --pretrained_path checkpoints/mp_rank_00_model_states.pt \
    -n 1 \
    --output-dir output
```

```bash
python -m eval_sim.eval_rdt_maniskill \
    --pretrained_path checkpoints/mp_rank_00_model_states.pt \
    --output-dir output
```