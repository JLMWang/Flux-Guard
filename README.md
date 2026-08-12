# PostFace
Flow-Guided Adversarial Face Editing for Postable Social Photo Privacy

# Authors
Jie Wang (Beijing University of Posts and Telecommunications-WangJie2023@bupt.edu.cn), Tao Wang (Nanjing University of Aeronautics and Astronautics-wangtao21@nuaa.edu.cn), Ru Zhang (Beijing University of Posts and Telecommunications-zhangru@bupt.edu.cn)
![](./FLUX_Guard/src/image.PNG)
# Abstract
Social photo sharing has become a major form of online self-presentation,while users increasingly seek to curate their facial appearance.However,faces posted on public platforms remain exposed to face recognition (FR)systems,leading to unauthorized identity linkage and associated privacy risks. Existing adversarial facial privacy methods are often constrained by fixed visual styles or source-preserving objectives, limiting their applicability to social photo sharing, where users seek personalized appearance curation. We therefore consider postable social photo privacy to require visual shareability, personalized appearance expression, and protection against unauthorized FR systems.To address these limitations,we introduce PostFace,a flow-guided adversarial face editing scheme for postable social photo privacy.It employs flow-trajectory control to align semantic manipulation with the generation process,enabling personalized facial editing,and performs perceptual-adaptive latent optimization to achieve identity protection through appearance-compatible edits.Experiments on public datasets and commercial FR APIs demonstrate competitive performance in identity protection and black-box transferability.Furthermore,PostFace remains highly effective after actual social-media processing and exhibits advanced postability in social-sharing scenarios.


## Prepare model checkpoints
Download the weights for victim models from [here](https://drive.google.com/file/d/19_Y0jR789BGciogjjoGtWNEv-5QBiCB7/view) and extract them to `./models`.

Download the Flux model from [here](https://huggingface.co/black-forest-labs/FLUX.1-dev).
## Run the code

```bash
python Flux-Guard/src/runfluxguard.py
```
