# 第四集六幕 · Midjourney 横屏提示词

上版失败原因：一条里塞了人名、十六人五种兵器、全套头饰，MJ 会画成群像乱炖、银角凤冠、现代兵。  
这版每条只做**一件事**：一个主光、一个动作、人物最多占画面三分之一。

**只复制英文灰框。** 中文是画面说明，不要贴进 MJ。  
横屏 `--ar 16:9 --style raw --stylize 100`。raw 是为了听话，不要改回 150。  
有金花/文广满意脸之后，在同一条末尾加 `--cref` 那张图。

金花只锁这几样：靛蓝短斗篷、齐腰短衣、裙到小腿、右后低髻、一根细银簪、露额头。  
文广只锁：国字脸、散乱长发、深褐皮甲、弧形佩刀。  
援兵是背景色块，不要点名人数和兵器清单。

---

## 第一幕 · 柳州古城战前

画面：俯瞰全城。人要有，但必须很小。还没起火，颜色先冷。

**中文说明**  
子夜俯瞰柳州城。城墙、城楼、黑瓦海。城头几个持戈小黑点，城楼有人敲鼓，一条巷里两点灯火在走。冷月。不要近景人脸。

```
cinematic wuxia film still, desaturated moonlight, 35mm film grain, high aerial wide shot of an ancient walled city at midnight, massive rammed-earth walls and a tall timber gate tower, a sea of dark-tile roofs, pale full moon, thin clouds, a few tiny spear guards on the battlements, one small drummer on the tower, two lantern dots moving in a stone lane, a handful of warm windows, ink black and cold moon white, quiet, people are specks --ar 16:9 --style raw --stylize 100 --no text, letters, watermark, modern objects, cars, streetlight, close-up faces
```

---

## 第二幕 · 文广撞栏冲牢道

画面：一个人，一个动作。侧前方中景。柳叶刀写成弧形佩刀，MJ 更认。

**中文说明**  
地下牢道。断裂木栏。高大武将肩撞断栏往镜头冲，右手弧形佩刀垂在身侧。逆火把他打成半剪影。后面只有官兵剪影。

```
cinematic wuxia film still, bold fire-orange grading, 35mm film grain, low-angle medium shot, a tall Chinese warrior bursting through broken wooden prison bars, square jaw, long loose hair, dark leather armor, a curved Chinese saber at his side catching firelight, striding toward camera, backlit by torches, soldier silhouettes far behind, wet stone vault, straw floor, charcoal and orange, one man one action --ar 16:9 --style raw --stylize 100 --no text, letters, watermark, modern objects, cars, guns, helmets
```

---

## 第三幕 · 金花率援兵杀入

画面：金花最大，援兵是她身后一排火把。不要写十六人、不要写五种兵器。

**中文说明**  
夜巷被火把照成一条红河。金花在画面左前冲来，靛蓝斗篷，裙到小腿，低髻细簪。身后一小队靛蓝短衣山民，只见火把、长矛、弓的剪影。

```
cinematic wuxia film still, bold red-orange grading, 35mm film grain, wide shot down a night stone street, closed wooden shops, a river of torchlight, a young Miao woman running toward camera in the left foreground, indigo short cloak, waist-length indigo jacket, mid-calf pleated skirt, low bun, one thin silver hairpin, bare forehead, torch raised, behind her a small band of mountain men in indigo as silhouettes with torches and spears, smoke sparks, distant gate tower, crimson versus indigo --ar 16:9 --style raw --stylize 100 --no text, letters, watermark, modern objects, cars, guns, silver horns, phoenix crown, turban, hanfu, armor
```

---

## 第四幕 · 城门伏兵张弓

画面：弓是主体。人在暗里。巷中撤退的人只做远处小影。

**中文说明**  
城门楼压在深处。前景暗处一排弓手拉满弦，只有火边轮廓。箭还在弦上。

```
cinematic wuxia film still, bold red-orange grading, 35mm film grain, wide shot, a huge iron-studded city gate and timber tower, military flags, a line of Song archers in shadow in the foreground drawing longbows full toward the lane, only orange rim light on helmets and bow curves, tiny fleeing figures far down the street, burning hay and smoke, the instant before release --ar 16:9 --style raw --stylize 100 --no text, letters, watermark, modern objects, cars, guns
```

---

## 第五幕 · 箭雨

画面：上半幅是箭，下半幅是小人和火。不要近人脸。

**中文说明**  
大远景。密箭斜划过橙红火光和浓烟。下面青石巷里一小群人在退，小得像蚁。

```
cinematic wuxia film still, bold red-orange grading, 35mm film grain, extreme wide night shot, a dense diagonal rain of arrows crossing the upper frame through orange firelight and black smoke, far below a tiny group running along a stone street toward a gate tower, burning hay piles, overturned stalls, half-hidden moon, people are ants, no faces --ar 16:9 --style raw --stylize 100 --no text, letters, watermark, modern objects, cars, guns
```

---

## 第六幕 · 中箭后上马

画面：马在中间。文广抱着已经软掉的金花往上放。护送的人推到背景里当火把点。不要写血、中箭、struck。

**中文说明**  
侧全景。深色战马。武将怒容把靛蓝姑娘横抱上马，她软靠他肩，斗篷后背一块暗红。远处几个火把护送。

```
cinematic wuxia film still, bold red-orange grading, 35mm film grain, medium-wide side shot, a dark horse, a tall warrior with loose hair and leather armor lifting a limp young Miao woman onto the saddle, her indigo cloak hanging, a dull dark stain on the back of the cloak, mid-calf skirt, pale face, low bun half loose, his jaw tight, a few torch-bearing men blurred in the background, burning gate alley, sparks, breakout --ar 16:9 --style raw --stylize 100 --no text, letters, watermark, modern objects, cars, guns, silver horns, phoenix crown, gore
```

---

出图顺序：先出第一幕定冷色，再出第三幕定金花靛蓝，这两张做 `--sref`，其余跟上。第三、六幕必须加金花 `--cref`，第二、六幕加文广 `--cref`，否则会换脸。
