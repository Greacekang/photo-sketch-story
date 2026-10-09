# Photo Sketch Story · 照片里的手绘小故事

作者：[凝言芝 / Greacekang](https://github.com/Greacekang)

把一张真实照片，变成自然延伸出手绘小故事的画面。保留照片中的主体、环境和光线，沿水线、道路、树枝、云或材质边缘，让真实世界接上温暖的绘本世界。
## 陈品展示
<img width="360"  alt="00e8b4dde2fac51e3b7620524c6bd2de" src="https://github.com/user-attachments/assets/db1314e7-a0fc-4414-a202-83fcdb985176" />
<img width="360"  alt="aa1d207d-5d05-4ea1-abf7-9a3f06811525" src="https://github.com/user-attachments/assets/b11238b9-9bab-41b1-9f67-6f5ff1d60066" />
<img width="360"  alt="0035f77c28c02102778964075c1f1997" src="https://github.com/user-attachments/assets/1cf69b60-eae2-41f3-ada8-038b883c0790" />
<img width="360"  alt="4c1564c3-a879-460f-b0f2-bfb716a08493" src="https://github.com/user-attachments/assets/9bd1a0ee-2cd0-4cfb-a5d1-11ced0cd874f" />
<img width="360"  alt="a3e7dcc00da6d2ce9052c6403352ae1f" src="https://github.com/user-attachments/assets/1d97439d-8c29-403a-a902-215a29f2f568" />
<img width="360"  alt="efbfafe9-28ed-4ad4-b7d8-37e736e25f72" src="https://github.com/user-attachments/assets/99ef77b0-3b02-4186-81f9-14138f27e3ec" />
<img width="360"  alt="25868a82012eabf1bda165941858dc74" src="https://github.com/user-attachments/assets/76794c02-1193-44f7-b378-9c041e3082b5" />
<img width="360"  alt="6ad84efc-aa6d-43e5-8be2-3df820f3d027" src="https://github.com/user-attachments/assets/e47ad0f9-cf35-4666-9c03-296fc83dec4e" />
<img width="360"  alt="570af762cd50da226820ceecf407f842" src="https://github.com/user-attachments/assets/5cd2fd44-0d14-40a7-83a4-e08aa6c6f95c" />
<img width="360"  alt="ffef6bed-0c1b-4c46-9600-f5d28c321444" src="https://github.com/user-attachments/assets/7ce9170e-ee1d-49a7-bdd2-cffc4cc6dfa4" />
<img width="360"  alt="3064357821bda851cc3e2eb100712cdb" src="https://github.com/user-attachments/assets/696b53bd-fce4-44d2-8457-08891a684312" />
<img width="360"  alt="8bf1b2d4-57d3-4bd5-acf5-ed23d29c1ee9" src="https://github.com/user-attachments/assets/19e4c3dc-9cec-4d5d-a9aa-6347fee8cdfc" />




## 效果与创作规则

- 真实摄影与稀疏的铅笔、墨线手绘结合，不使用固定上下分屏模板。
- 根据照片选择故事切入点、延伸方向和构图。
- 人物或动物数量由故事和画面美观度决定；角色可以分别做不同的清晰动作。
- 默认不加文字；可以选择治愈、搞笑、旅行、节日或童趣氛围。

## 使用

需要一个支持读取 Skill 指令、查看上传照片、编辑生成图片的 AI 环境。Skill 提供创作规则，本身不包含生图模型。

在 Codex 中，将本仓库的 `photo-sketch-story` 文件夹放入个人 Skill 目录（本次验证环境使用 `~/.codex/skills/`）。如果已有同名 Skill，先备份原版本，再决定是否替换。重新打开会话，上传一张照片，输入：

```text
使用 $photo-sketch-story，把这张照片做成治愈的小故事，不要文字。
```

其他例子：

```text
用 $photo-sketch-story 做这张狗狗照片，搞笑一点，自动构图。
```

```text
把这张旅行照做成温暖小故事，横版，不要文字。
```

可选输入：氛围、比例（自动 / 9:16 / 1:1 / 16:9）、文字模式和简短创作偏好。只给照片时使用默认选项。

也可以在支持图片编辑生成的聊天产品中，将 `SKILL.md` 正文作为创作指令使用。不同模型、上下文和随机采样会带来不同结果，不保证复现同一张图。

## 文件

`photo-sketch-story/SKILL.md` 是完整创作指令。此版本保留已确认的原文，并采用用户最终确认的角色数量与独立动作规则。

本仓库首先发布独立 Skill 源文件；尚未打包为插件商店安装包。

## English

Photo Sketch Story turns a real uploaded photograph into a refined photo-and-sketch micro-story. It preserves recognizable photographic subjects while extending the scene into sparse pencil/ink illustration.

Character counts and individual actions are chosen according to narrative needs and composition. An image-capable AI environment is required; this repository does not include an image model.
