## Fixing Audio Hissing In Ubuntu

Imported from old website



Many people have complained of a wierd wave hiss in there headphones. Nealy all ubuntu distros I have tried this sound will play everytime there even if there is no audio playing.

My Fix:
```

echo 0 | sudo tee /sys/module/snd_hda_intel/parameters/power_save_controller
echo 0 | sudo tee /sys/module/snd_hda_intel/parameters/power_save

```
Some reason this works 🙂 I just found it on some forum somewere

hope this fixed it…

 