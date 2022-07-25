# KD-BU
A torch Implementation of paper "Detecting Adversarial Samples from Artifacts" \
Original Code (Tensorflow) : https://github.com/rfeinman/detecting-adversarial-samples

Usage

    1. python scripts/train_model.py -d=mnist -e 20 -b 256
    2. python scripts/craft_adv_samples.py -d=mnist -a=fgsm -b 256
    3. python scripts/detect_adv_samples.py -d=mnist -a=fgsm -b 256
