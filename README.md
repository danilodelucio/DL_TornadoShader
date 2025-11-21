
![DL_TornadoShader - Thumbnail v1](https://github.com/user-attachments/assets/4b2d16ac-6fa1-424f-a8fa-2ff42956984b)

# DL_TornadoShader
This Blender file provides a Shader to create a tornado effect without simulation, based on Volume Shader.

![overall_v001](https://github.com/user-attachments/assets/ab523b4f-fcfa-4e62-b01f-5d70fd41228b)
![vfx_v001 2](https://github.com/user-attachments/assets/5ffbcb4d-b8a3-4170-95b1-5ba752746af4)


---

This tool was inspired by **Bad Normals**' tutorial, and you can check it out here:
> https://www.youtube.com/watch?v=0bCbLY7s3zQ

If you want to check my VFX shot that I used my tornado version, please check it out:
> https://www.youtube.com/watch?v=0O4ICi_XhgM

I optimized the entire setup into one node, with all the necessary parameters easily accessible to the user.

![DL_TornadoShader - Before and After v1](https://github.com/user-attachments/assets/8a92ac6c-35c1-48b2-8215-e7225dd08b95)

# Compatibility

This tornado effect works for both **Eevee** and **Cycles**, and was tested in **Blender 4.4/5.0**.

# Tornado Enhancement

You can achieve better results by adjusting the **Volume** settings.

## Eevee
- Change the **Resolution** to **1:2** (or whatever you like);
- Disable the **Custom Range** option to avoid clipping the tornado.

<img width="593" height="533" alt="image" src="https://github.com/user-attachments/assets/a341ee0a-9da4-4051-8bdc-89d790b49fad" />

## Cycles
- Enable **Biased** option;
- Decrease the **Step Rate Render** and **Viewport** to **0.10** (or whatever you like).
<img width="591" height="316" alt="image" src="https://github.com/user-attachments/assets/f147828c-c466-4132-88aa-3c84884e5555" />
