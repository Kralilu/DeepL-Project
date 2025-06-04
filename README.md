## DeepL Project

## How to clone

Since there is a submodule, to properly clone the project run:
`git clone --recurse-submodules https://github.com/Kralilu/DeepL-Project.git`

If you clone this repo without --recurse-submodules you can run:
`git submodule update --init --recursive`

## Paper Review
***bold*** Visual Autoregressive Modeling: Scalable Image Generation via Next-Scale Prediction ***bold***
https://proceedings.neurips.cc/paper_files/paper/2024/hash/9a24e284b187f662681440ba15c416fb-Abstract-Conference.html

## Presentation plan

***bold*** Visual Autoregressive Modeling: Scalable Image Generation via Next-Scale Prediction ***bold***
- Introduction
    - Quickly talks about types of generative models
    - Why VAR
- AutoRegressive Models
    - How do AR models work
        - Sequential prediction process
        - Common architectures (e.g., PixelRNN, PixelCNN)
    - AR models weaknesses
        - Slow sampling speed
        - Limited scalability to high resolutions
        - Issue with unilateral premisse
- Present the paper VAR
    - The difference between VAR and AR
        - Next-scale prediction vs. pixel-by-pixel prediction
        - Structure overview
    - The advantages of VAR
        - Improved scalability
        - Faster image generation
        - Better performance on large images
    - Training, testing details
        - Dataset used
        - Training procedure and hyperparameters
        - Evaluation metrics
    - Results (talk about FID, etc.)
        - Quantitative results (FID scores)
        - Qualitative results (sample images)
        - Comparison with baseline AR models, Diffusion models and GAN models
- Demo
    - Live demonstration of VAR model
    - Walkthrough of code or results
- Conclusion
    - Summary of key findings
    - Future directions and open questions

