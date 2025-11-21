
![DL_TornadoShader - Thumbnail v1](https://github.com/user-attachments/assets/4b2d16ac-6fa1-424f-a8fa-2ff42956984b)

# DL_TornadoShader
Free tornado shader for Blender, without simulation.

This tool was inspired by Bad Normals' tutorial, and you can check it out here:
> https://www.youtube.com/watch?v=0bCbLY7s3zQ

If you want to check my VFX shot that I used my tornado version, please check it out:
> https://www.youtube.com/watch?v=0O4ICi_XhgM

---
I optimized the entire setup into one node, with all the necessary parameters easily accessible to the user.

<img width="981" height="835" alt="image" src="https://github.com/user-attachments/assets/3165f7fb-a50c-43ad-9d6f-fa3305b895f0" />

# Render Engine Compatibility

This tornado effect works for both Eevee and Cycles.

# Tornado Enhancement

You can get better results by adjusting the Volume settings.

## Eevee
- Change the **Resolution** to **1:2** (or whatever you like);
- Disable the **Custom Range** option to avoid clipping the tornado.

<img width="593" height="533" alt="image" src="https://github.com/user-attachments/assets/a341ee0a-9da4-4051-8bdc-89d790b49fad" />

## Cycles
- Enable **Biased** option;
- Decrease the **Step Rate Render** and **Viewport** to **0.10** (or whatever you like).
<img width="591" height="316" alt="image" src="https://github.com/user-attachments/assets/f147828c-c466-4132-88aa-3c84884e5555" />
