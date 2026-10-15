# 图文案例与生成提示词

这些案例由 Codex 内置 `image_gen` 生成。下面保留了调用语句和本次实际使用的完整提示词，方便试用和调整；再次生成时，构图、人物和文字可能不同。

## 默认彩色：骑车摔进水坑

三个散落场景分别画出骑行、失衡和摔倒。未指定配色时，默认使用几种高饱和的旧版 Paint 颜色。

```text
$oops-paint 画一个人骑车摔进水坑的事件解释图
```

![默认彩色：骑车摔进水坑](images/puddle.png)

完整生成提示词：

```text
Use case: illustration-story
Asset type: landscape PNG example for a rough MS Paint doodle skill README.
A rough MS Paint explanation doodle about a person riding a bike, hitting a puddle, losing balance, and falling.
Show exactly 3 loosely scattered mini-scenes on one plain white page with lots of blank space: the person riding toward a puddle, the front wheel in the puddle with the person wildly losing balance, then the person sprawled harmlessly in the puddle beside the fallen bike. Repeat the same awkward little person and recognizable bike, with mismatched scene sizes and uneven placement, no comic boxes.
Draw crude warped people and bike shapes with thin shaky black mouse lines, repeated hesitant strokes, broken contour corrections, mostly unfilled interiors, rough scratchy color marks, huge circular eyes and exaggerated flailing poses. Only 2 tiny hand-written Chinese notes in the whole picture, exactly "哎？" by the loss of balance and "扑通" by the fall. No other text, no arrows, no sequence numbers, no labels or headings.
a few harsh default MS Paint palette colors,
crude failed bucket fills,
color bleeding outside broken outlines,
accidental white gaps,
wrong regions filled,
no gradients,
no shading,
no professional color harmony
Use only black, harsh red, blue, green and yellow marks on white; keep most of the page white. Allow the shirt to have a small wrong-color fill in one fragment. Do not add buildings, crowds, background decoration or unrelated props.
Looks like a genuine amateur MS Paint explanation doodle with loose scattered mini-scenes, extra scratchy linework, visibly broken outlines, messy repeated color strokes, half-finished scribble texture and obvious correction marks. Actions should remain readable even though the drawing is clumsy and failed; not a polished comic, storybook, elegant naive illustration or professional infographic.
```

## 黑白：捡到钱包追上失主

四个场景表现发现钱包、弯腰捡起、追赶和归还。黑色轮廓配灰色乱刷，画面不使用彩色。

```text
$oops-paint 只用黑白，画一个人在超市门口捡到钱包又追上失主
```

![黑白：捡到钱包追上失主](images/wallet.png)

完整生成提示词：

```text
Use case: illustration-story
Asset type: landscape PNG example for a rough MS Paint doodle skill README.
A rough MS Paint explanation doodle about a person finding a wallet and chasing down its owner near a supermarket entrance.
Show exactly 4 loose scattered mini-scenes on one plain white page with large empty areas and uneven spacing: the owner walks away from a crudely drawn store doorway while a wallet lies on the ground, the finder bends over to pick up that wallet, the finder runs after the owner while raising the wallet high, then the finder hands it back and the owner reaches out with surprise. Repeat the same two awkward people and same simple wallet. Use uneven fragment sizes and no panel grid.
Draw warped people, store doorway and wallet with thin shaky black mouse lines, broken and retraced contours, loose gray pencil scribbles only inside some clothing and the wallet, mostly unfilled white interiors, giant round eyes and exaggerated running and reaching poses. Only 2 tiny hand-written Chinese phrases total, exactly "等等" near the runner and "你的" near the returned wallet. No other text, no arrows, no sequence numbers, no labels or headings.
black outlines with messy gray pencil-scribble fills on a plain white canvas,
no color anywhere,
gray hand-scribbled fill texture is allowed,
no gradients,
no soft rendered lighting,
no material rendering,
no polished grayscale painting
Absolutely no hue anywhere: white, black and neutral gray only, including every line and letter. No red, blue, green, yellow, brown or purple. The store is only a crooked doorway, not a full decorated building; no signs, crowds or unrelated objects.
Looks like a genuine amateur MS Paint explanation doodle with loose scattered mini-scenes, scratchy linework, broken contour corrections, messy hand-scribbled gray texture and half-finished forms. Keep the four actions clear; not a polished comic, storyboard, storybook, elegant naive illustration or professional infographic.
```

## 红黑：地铁门夹包

四个场景表现上车、夹包、拉扯和脱困。红色只用于包和包带，其余用黑线和白底。

```text
$oops-paint 只用红黑，画地铁门夹包的荒诞重现图
```

![红黑：地铁门夹包](images/bag.png)

完整生成提示词：

```text
Use case: illustration-story
Asset type: landscape PNG example for a rough MS Paint doodle skill README.
A rough MS Paint explanation doodle about a subway door catching a passenger's bag in an absurd harmless incident.
Show exactly 4 loose scattered mini-scenes on one plain white page with large blank gaps: the passenger steps into the subway carrying a red bag, the two crooked door leaves close with the red bag visibly caught between them, the passenger inside tugs the stretched bag strap with an absurd leaned-back pose, then the doors reopen and the passenger tumbles backward clutching the released bag. Repeat the same awkward person, bag and recognizable pair of train doors. Vary the fragment sizes and positions with no regular comic grid and no panel borders.
Draw crude warped people, bag and train door shapes with thin shaky black mouse lines, repeated hesitant scratches, visibly broken contours, half-corrected outlines, mostly unfilled interiors, rough red scribble fills with white gaps, giant circular eyes and exaggerated grabbing and tugging poses. Only 2 tiny hand-written Chinese notes total, exactly "夹住了" by the trapped bag and "啊" near the final backward tumble. No other text, no arrows, no sequence numbers, no labels or headings.
red and black only, crude failed bucket fills, color bleeding outside broken outlines, accidental white gaps, wrong regions filled, no gradients, no shading, no professional color harmony.
Use only black and saturated red marks on a plain white canvas; no blue, green, yellow, brown, purple or gray fills. Keep the scene airy, with no realistic subway interior, passengers, advertising or unrelated props.
Looks like a genuine amateur MS Paint explanation doodle with loose scattered mini-scenes, extra scratchy linework, messy repeated red strokes, broken contour corrections and obvious half-finished scribble texture. The caught bag and exaggerated tugging must remain clear; not a polished comic, storybook, elegant naive illustration or professional infographic.
```


## 拾金不昧

默认彩色。四个散落片段画出发现钱包、拿起寻找、失主摸空口袋和归还钱包，只留“谁的”“还你”两处短字。

原始需求（加上 Skill 名即可调用）：

```text
$oops-paint 跑一个 拾金不昧
```

![拾金不昧](images/honesty.png)

本次由内置 `image_gen` 生成，实际完整提示词如下；再次生成时，画面可能不同。

```text
Use case: illustration-story
Asset type: landscape PNG example for the Oops Paint skill.
A rough MS Paint explanation doodle about 拾金不昧, an honest person finding a lost wallet and returning it to its owner.
Show exactly 4 loose scattered mini-scenes on a plain white page with large blank areas, uneven sizes and no comic grid: an awkward little person notices a wallet containing a few money notes on the ground, the person picks it up and looks around with an exaggerated searching pose, the person spots the owner patting empty pockets in panic and raises the wallet, then the person returns the wallet to the relieved owner. Repeat the same finder, owner and wallet; do not add other people or scenery.
Make the people deliberately badly mouse-drawn: squashed round heads, giant circular eyes, bent stiff stick limbs, vague blob hands, visibly broken black outlines, many interrupted tentative strokes, retracing that drifts away from the first contour, unfinished details and scratchy fills. Keep actions recognizable and expressions overacted. Only 2 very short hand-written Chinese phrases on the whole image, exactly "谁的" near the searching pose and "还你" near the handover. No title, no other writing, no arrows, no sequence numbers, no comic boxes.
a few harsh default MS Paint palette colors,
crude failed bucket fills,
color bleeding outside broken outlines,
accidental white gaps,
wrong regions filled,
no gradients,
no shading,
no professional color harmony
Use black, crude red, blue, green and yellow marks only on the white page, mostly unfilled interiors. Color should look like impatient short mouse scribbles and small failed fills, not smooth paint. Allow a small wrong-color patch on one shirt.
Looks like a genuine failed amateur MS Paint explanation doodle, casually scattered on a very white page with wobbly retraced broken contours, lopsided shapes, loose exaggerated actions and only a few tiny handwritten notes; not a polished comic, storybook, stylish naive illustration or professional infographic.
```

## 黑白：曹冲称象

大象上船记下水位，象下船后装入石头，船沉到同一水位，再称出这些石头的总重。三个场景只用黑线和不均匀的灰色乱刷，保留“记水位”“换石头”“称石头”三处短字。

原始需求（加上 Skill 名即可调用）：

```text
$oops-paint 跑一个黑白的 曹冲称象
```

![黑白：曹冲称象](images/weighing.png)

本次由内置 `image_gen` 生成，实际完整提示词如下；再次生成时，画面可能不同。

```text
Use case: illustration-story
Asset type: landscape PNG example for the Oops Paint skill.
A rough black-and-white MS Paint explanation doodle of the Chinese story 曹冲称象, in which Cao Chong weighs an elephant indirectly by replacing its load in a boat with stones and then weighing the stones.
Show exactly 3 loose scattered mini-scenes on one plain white page with lots of blank space and unequal scene sizes, no comic grid. In one scene a recognizable elephant stands inside a simple boat floating low in scribbled water; a small boy in a crude ancient tunic leans down and makes a short horizontal mark on the side of the hull exactly at the water surface. In another scene the elephant has left the boat and stands on shore, while the same boy loads stones into the now elephant-free boat until the surface of the water reaches that same short hull mark; show a pile of stones in the boat. In the last smaller scene the same boy weighs these stones on a simple crooked beam balance on shore, with remaining stones alongside; there is no elephant on the weighing scale. The elephant, boat and stones must be recognizable; do not combine elephant and stone loads in the boat.
Use thin shaky black mouse lines, naive warped proportions, broken and open contours, repeated correction scratches, a lopsided little boat, irregular stone blobs and an awkward elephant with giant ears and a long trunk. Fill parts of the elephant, boat, clothes, stones and water with irregular gray pencil-like scribbles while leaving white gaps. Exactly 3 very short hand-written Chinese notes total: "记水位", "换石头", "称石头", beside the corresponding actions. The waterline mark is only a short horizontal line, never an arrow. No title, no other text, no equations, no visible sequence numbers, no arrows and no panel borders.
black outlines with messy gray pencil-scribble fills on a plain white canvas,
no color anywhere,
gray hand-scribbled fill texture is allowed,
no gradients,
no soft rendered lighting,
no material rendering,
no polished grayscale painting
Absolutely all water, clothes, objects and letters are black, neutral gray and white only; no blue water or colored writing. Keep the background empty, no decorative landscape or extra crowd.
Looks like a genuine failed amateur MS Paint explanation doodle with loose scattered scenes, exaggerated pointing and bending poses, scratchy half-corrected outlines and messy patchy gray scribbles, not a polished comic, elegant picture book, history painting, neat storyboard or professional infographic.
```


生成后用内置 `image_gen` 调整了前两只船的水面，使水线与船身上的短记号对齐，保留其余画面。实际编辑提示词：

```text
Use case: precise-object-edit
Asset type: landscape PNG example for the Oops Paint skill.
Edit this existing rough black-and-white 曹冲称象 image with one local correction only: in BOTH boat scenes, make the visible surface of the water touch and run through the center of the short bold black horizontal waterline mark on the boat's outer hull. The first hull mark is currently visibly above the water, and the second hull mark is also above the water; this is the only error to correct.
Keep each short hull mark at the same proportional height on its boat side, and adjust the immediately surrounding rough water surface upward so it visibly meets that mark. Show the lower hull partly submerged below this new surface in both scenes, with a clear matching amount of hull above the water. The elephant-loaded boat and the stone-loaded boat must show the same relative draft. A horizontal water ripple may meet the short black mark naturally; do not turn the mark into an arrow or add a leader line.
Preserve the original elephant, boy, stones, boat shapes, all three scattered scene positions and sizes, the balance weighing stones, the exact three handwritten notes "记水位", "换石头", "称石头", rough shaky broken mouse lines, uneven neutral-gray scribbles, white background and large empty areas. Do not redraw or beautify anything else. Keep exactly three scenes, no new props, no extra words, no numbers, no arrows and no panel borders.
black outlines with messy gray pencil-scribble fills on a plain white canvas,
no color anywhere,
gray hand-scribbled fill texture is allowed,
no gradients,
no soft rendered lighting,
no material rendering,
no polished grayscale painting
Keep the genuine failed amateur MS Paint explanation doodle look, not a polished comic, storybook, history painting or professional infographic.
```


## 红黑：守株待兔

原始需求没有指定成语，本例选用“守株待兔”。三个场景画兔子撞到树桩、农夫捡兔和坐等下一只兔子。白底上只画红黑线条，保留“白捡”“还等”两处短字。

原始需求（加上 Skill 名即可调用）：

```text
$oops-paint 只用红黑，画一个成语解释图
```

![红黑：守株待兔](images/waiting.png)

本次由内置 `image_gen` 生成，实际完整提示词如下；再次生成时，画面可能不同。

```text
Use case: illustration-story
Asset type: landscape PNG example for the Oops Paint skill.
A rough MS Paint explanation doodle of the Chinese idiom 守株待兔: a farmer finds one rabbit after it accidentally hits a tree stump, then foolishly keeps waiting beside the stump for another rabbit.
Show exactly 3 loosely scattered mini-scenes on one white page with generous blank gaps, unequal sizes and no comic grid. One scene shows a running rabbit harmlessly bumping its head against a short obvious tree stump with little wobble motion strokes, no blood. Another scene shows a farmer in a crude simple tunic and floppy hat bending down to pick up the same limp-looking but non-gory rabbit beside the stump, with an absurd delighted expression. The final scene shows the same farmer sitting empty-handed and staring intently at the same stump, waiting in vain; no rabbit arrives in that final scene. Keep all fragments tied to this single idiom; no other fable props, no extra animals, no unrelated farming objects.
Draw the farmer, rabbit and stump with thin shaky black mouse outlines, large round eyes, awkward limbs, warped proportions, open broken contours, multiple half-corrected retracing scratches and mostly unfilled white interiors. Use small messy red scribble patches on the farmer's tunic and hat only, so red is clearly clothing color rather than injury. Only 2 tiny hand-written Chinese notes total: "白捡" by the farmer picking up the rabbit, and "还等" by the sitting farmer. No title, no other words, no arrows, no sequence numbers and no comic boxes.
red and black only, crude failed bucket fills, color bleeding outside broken outlines, accidental white gaps, wrong regions filled, no gradients, no shading, no professional color harmony.
All lines and marks are black or saturated red on a plain white canvas, with no other colors and no gray fill. Keep the rabbit and stump mostly white inside black outlines. The collision is silly and mild, with no wounds, blood or gore.
Looks like a genuine failed amateur MS Paint explanation doodle with loose scattered mini-scenes, scratchy broken corrections, uneven uncertain lines, patchy messy red scribbles, giant empty white areas and exaggerated clumsy poses, not a polished comic, storybook, elegant naive illustration or professional infographic.
```

## 更潦草：哑巴吃黄连

默认彩色。三个片段画出拿起黄连、入口和有苦说不出；最后的苦脸被刻意夸张，碎线、重描、漏填和乱刷也更多。短字只留“黄连”“苦”和省略号。

原始需求（加上 Skill 名即可调用）：

```text
$oops-paint 画一个哑巴吃黄连，更潦草一点，保留两三处短字
```

![更潦草：哑巴吃黄连](images/bitterness.png)

本次由内置 `image_gen` 生成，实际完整提示词如下；再次生成时，画面可能不同。

```text
Use case: illustration-story
Asset type: landscape PNG example for the Oops Paint skill.
A rough, extra careless MS Paint explanation doodle of the saying 哑巴吃黄连: the same mute person eats a very bitter piece of huanglian herb and has bitterness they cannot put into words.
Show exactly 3 very loosely scattered mini-scenes on one plain white page with a lot of empty space and noticeably unequal sizes, with no comic grid. One scene shows an awkward person cautiously holding a small yellow chopped rhizome close to the face before tasting it. Another scene shows the same person biting that herb, shoulders shooting up and eyes popping in startled reaction. The last larger scene shows the same person with an absurdly twisted bitter face, bulging watery eyes, crooked clenched mouth, hunched torso and wildly bent arms, trying to speak but unable to get words out. Keep the herb as small irregular yellow root pieces; do not draw candy, peppers or lemons. No unrelated bystanders or extra props.
Make this deliberately rougher and less neat than a normal doodle: fragmented thin black mouse lines, many broken contours, repeated retracing drifting in different directions, stray correction scratches, squashed lopsided head shapes, badly matched eyes, short spiky hairs, vague blob hands and simple crooked limb sticks. Keep each action understandable. Fill only a few small regions with frantic repeated short color strokes, with very obvious white gaps, misfills and spills past the contours. Only 3 tiny hand-written Chinese notes total, exactly "黄连" next to the herb in the first scene, "苦" by the tasting scene and "……" by the final attempted speech. No title, no other text, no arrows, no sequence numbers, no panels or speech balloons.
a few harsh default MS Paint palette colors,
crude failed bucket fills,
color bleeding outside broken outlines,
accidental white gaps,
wrong regions filled,
no gradients,
no shading,
no professional color harmony
Use black, harsh yellow, red, blue and green scribbles on white, with mostly white interiors. Make the bitter facial reaction much more exaggerated than the other poses; do not rely on labels to explain it. No realistic medical imagery.
Looks like a genuine rushed failed amateur drawing made with an old MS Paint mouse: extra scratchy linework, messy repeated color strokes, broken contour corrections and obvious half-finished scribble texture, loose thrown-on-the-page placement and generous white areas; not a polished comic, storybook, elegant naive illustration, refined character sheet or professional infographic.
```

生成后用内置 `image_gen` 去掉了“黄连”旁误出的指示箭头，保留其余画面。实际编辑提示词：

```text
Use case: precise-object-edit
Asset type: landscape PNG example for the Oops Paint skill.
Edit this existing rough MS Paint image of 哑巴吃黄连. Make exactly one change: erase the tiny black arrow between the handwritten "黄连" note and the herb in the top-left scene, restoring white background in that tiny gap. Keep the "黄连" writing itself, the yellow herb and every other mark unchanged.
Preserve the same three scattered scenes, all faces and exaggerated poses, the extra scratchy broken mouse linework, messy scribble fills, white gaps, all colors, framing, image dimensions, and the three sparse handwritten notes "黄连", "苦" and "……". Do not redraw, tidy or beautify the image. No arrows anywhere, no numbering, no comic boxes and no added text.
a few harsh default MS Paint palette colors,
crude failed bucket fills,
color bleeding outside broken outlines,
accidental white gaps,
wrong regions filled,
no gradients,
no shading,
no professional color harmony
Keep the same raw failed amateur MS Paint look. The person is mute and has bitterness they cannot express; do not add any explanatory caption or medical interpretation.
```
