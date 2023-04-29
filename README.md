# Assignment-14

## Problem Statement

![image](https://user-images.githubusercontent.com/120099863/235308702-ea4d754d-98fc-4065-8d43-f927a7612426.png)

## Textual Inversion

Prompt used for generation of images: "dancing astronaut"

Generated images using different Styles:

| Style: None | Style: midjourney-style |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/120099863/235308920-afa1db02-5bef-4c2a-b1d4-2e5465383c7d.png) | ![image](https://user-images.githubusercontent.com/120099863/235308960-1ec6fc03-269b-4f13-8749-7d9f78566d0d.png) |

| Style: birb-style | Style: summie-style |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/120099863/235309699-cbe9b594-c39a-4530-8212-bc3fa828ef93.png) | ![image](https://user-images.githubusercontent.com/120099863/235309727-af35c3e7-323d-4f3d-8d18-10d99ee07303.png) |

| Style: illustration-style | Style: m-geo |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/120099863/235309782-f9d3a84e-cbb9-4a97-b9c0-d66e15b62913.png) | ![image](https://user-images.githubusercontent.com/120099863/235309795-0860c1e7-fc6b-4cbd-85b4-3d88c91cd50c.png) |

## Loss Function

Image is generated for promp "mermaid". Embedding of generated image is used as ground truth for loss function. Following images are created with different styles:

| Style: None | Style: midjourney-style |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/120099863/235309991-ab4603d8-88b7-45f0-bb1b-312103eeec90.png) | ![image](https://user-images.githubusercontent.com/120099863/235310007-8e36d94f-8465-455a-b5e6-6676e46d73d8.png) |

| Style: birb-style | Style: summie-style |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/120099863/235310026-9eae14ce-77cc-4044-b36a-bdb218cfc89d.png) | ![image](https://user-images.githubusercontent.com/120099863/235310041-40aba65a-585e-4df8-b33b-2c576eaa0d3c.png) |

| Style: illustration-style | Style: m-geo |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/120099863/235310059-7152c2ed-e976-4d98-9c2b-901ec227f91e.png) | ![image](https://user-images.githubusercontent.com/120099863/235310080-72977dc1-a2ed-4693-ab93-520ab58cc08b.png) |
