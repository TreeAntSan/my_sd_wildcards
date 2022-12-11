# stable_diffusion_wildcards
This is my personal collection of wildcards for [Automatic1111's WebUI Wildcards plugin](https://github.com/AUTOMATIC1111/stable-diffusion-webui-wildcards), currently concentrating on making softcore photo realistic generations through Stable Diffusion

I've been enjoying creating really odd and diverse softcore images that just really push the bounds of what one could expect to find on real life adult photo collections.

My thing women with six-pack abs, low body fat, and muscles that would make Bruce Lee nod in appreciation. While ladies like that [aren't good for anything](https://youtube.com/clip/UgkxraQJ0N5qSPsmkFRiKlElfVS7zfTG3jvU) but looking at, I feel like it's hard to find stuff that lights up that kink over the years of collecting and enjoying adult materials.

So, if you got some vague genre of lady that you just wish there were more of, I really encourage you to give wildcards a try and start by downloading my collection to then start your own.

Start with my files, and maybe you're into women who are overweight, have really pale skin and freckles, and have them rubbing suntan oil on themselves or something. Well, you can add all kinds of wildcards describing women on the heavier side, with various different skin and pigmentation variations, and try different keywords and settings to get these women covered in white lotion.

## Suggestions to get started
I've had great luck with [Smirking Face's](https://www.patreon.com/smirkingface) initial general-purpose explicit model "EB_1.0", which can be [found here](https://www.patreon.com/posts/released-models-73689798), and merging it with SDv1.5 (mostly a 50/50 merge so far).

I suspect Zeipher (f99, f111) and s4269674 would work well, too! You can find a bunch of models on the ["sdmodels" rentry paste](https://rentry.org/sdmodels).

### Example prompt
```
((__angle-various__ __framing-normal__)), __photo-quality__. (__ages-18-45__ __nationalities-world__ __description-poor__ __subject-various__). (((Naked))), bare chest, __boobs-small__. __hair-various__ ((__face-good__)), __expression-all__. (((__body-abs__))), __body-skinny__, __decoration-marked__. __lighting-various__. High detail face. Bright eyes. Sharp. __location-prisons__, __vagina-various__. narrow hips. ((__pose-stand__))
```

### My negative prompt
Just what I've been using; note the presense of "curvy" and "big boobs" - you might want those!
```
man, boy, male, curvy, deformed, blurry, bad anatomy, disfigured, poorly drawn face, mutation, mutated, extra limb, ugly, poorly drawn hands, missing limb, blurry, floating limbs, disconnected limbs, malformed hands, blur, out of focus, long neck, big boobs, long body, panties, shiny, (bra), (monochrome), (black and white photo)
```

### And basic settings I've enjoyed
Euler A; 30 steps @ CFG Scale 10.0
or
Euler; 50 steps @ CFG scale 11.0

## Basic instructions
Install [the plugin](https://github.com/AUTOMATIC1111/stable-diffusion-webui-wildcards) (it takes a minute but it's pretty easy).

Download my files as a ZIP (or if you know how to clone git repos, do that) and create a `./wildcards` directory in the root directory of the Automatic1111 web-ui tool.

In your prompt simply take the file name, such as for `hair-various.txt`, and write `__hair-various__` into your prompt. And the plugin will randomly pick (based on the seed) an option from the list.

Files are newline-delimited, and blank lines will be represented as blank strings (so, unless you want to occasionally not have a wildcard present, don't leave any blank lines).
