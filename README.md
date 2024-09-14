# LoRA Training
My notes on training LoRA

### Some raw links till I can organize it

* https://github.com/bmaltais/kohya_ss
* I'm trying to use the LoRA trainer on CititAI for FLUX but came across this: https://civitai.com/articles/3105/essential-to-advanced-guide-to-training-a-lora
* https://civitai.com/articles/138/making-a-lora-is-like-baking-a-cake
* If training a LoRA for a specific kind of cat like a Siamese, your regularlization images should be of many different cats.
* Use activation tag as the first tag in every training image.
* Try SD1.5, 512x512, DDIM and check results. Only use base models.
* Sample base setings from Koyass if you are doing it in Python: https://gist.githubusercontent.com/Poiuytrezay1/14d146290a08afedc8ea07d7c79f2049/raw/06ffed6ed9ad75864f4e80d4560fd25d9c4815ac/base.json ---> right-click and save as kohya-ss
* That's probably not good for Flux. Use settings suggested in the Essential article if doing it all by code and not using CivitAI.
* Clip skip: 1 for realism
* Network dimension bewteen 1 and 16 (?)
* If using one unique Activation tag, use Keep N Tokens set to 1. (ie keep just the first token)
* https://openmodeldb.info/models/4x-realesrgan-x4plus - For realism


## References

* https://rentry.co/59xed3
* https://github.com/bmaltais/kohya_ss/wiki/LoRA-training-parameters
* Training a Character Lora for SD1.5: https://civitai.com/articles/138/making-a-lora-is-like-baking-a-cake: Extremely long! Might be a waste of your time! But it is detailed. For anime, less important for realism.
* 
