# WGDiff
The source code of our paper "Efficient Guided Diffusion Toward Adverse Weather Image Restoration", which will be available after the paper is accepted.

# Data preparation
Please refer to the Dataset utilized in paper "Restoring vision in adverse weather conditions with patch-based denoising diffusion models"

# Train
1.Modify the yml file in folder "config".

2.Simply run "python train_diffusion_allweather_union.py"

3.The weight will be saved in folder "ckpt/exp_name"

# Eval
1.Modify hyperparameters in "eval_diffusion.py", including input folder, gt_folder (if exists), save_folder, yml path, weight path, sampling steps, patch size, overlapping size, etc.

2.Run "python eval_diffusion.py"

3.Results will be saved in "save_folder"
