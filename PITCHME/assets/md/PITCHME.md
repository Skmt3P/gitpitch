
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="TOP"  -->
<div class="west span-100 text-white startend">
<span style="font-size: 4rem">Why Finland</span>
</div>

---
<!-- .slide: data-background-image="./assets/md/assets/profile_green.png" data-background-size="100% 100%" data-background-position="center" data-background=" " data-background-repeat=" " data-background-transition="slide" -->

<!-- .slide:  data-menu-title="自己紹介"  -->
<div class="north-west text-white">
<span style="font-size: 3rem">Who am I !?</span>
</div>
<div class="west span-65 text-white">
名前：坂本さん ( @Skmt3P ) <br>
肩書：個人事業主/エンジニア <br>
拠点：**東京都町田市** <br>
技術：Vue.js, Nuxt.js 他 <br>
活動：4月からVue案件
</div>
<div class="east span-35">
<img class="shadow"  src="./assets/md/assets/profile_qr.png"  />
</div>

---
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="テーマ選定1"  -->
# 今日のテーマどうしよ？

+++
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="テーマ選定2"  -->
# Nuxt.js?

+++
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="テーマ選定3"  -->
# Firebase?

+++
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="テーマ選定4"  -->
# CircleCI?

+++
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="テーマ選定5"  -->
# 技術書執筆やRe:VIEW?

+++
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="テーマ選定6"  -->
# フリーランスの実態?

+++
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="テーマ選定7"  -->
# それとも...

---
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="テーマ選定8と告知"  -->
<div class="north span-100 headline">
<h4>それらは技術書典6(こ09)で本出します！</h4>
</div>
<img class="shadow"  src="./assets/md/assets/qrcode.png"  />

---
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="テーマ選定9"  -->
# 今日は！

---
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="テーマ決定"  -->
<div class="north span-100 headline">
<h4>無思考型個人開発(=造語)の話をしよう！</h4>
</div>
![Image](./assets/md/assets/neet_man.png)

---
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="例"  -->
<div class="north span-100 headline">
<h4>個人開発はロジックだけ考えて生きたい</h4>
</div>
<div class="west span-40">
❌ 環境構築 <br>
❌ デザイン <br>
❌ 共通する部品 <br>
❌ フォルダ構成 <br>
❌ ソースの書式 <br>
❌ DevOps 等
</div>
<div class="east span-60">
![Image](./assets/md/assets/neet_woman.png)
</div>

---
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="主張"  -->
<div class="north span-100 headline">
<h4>"Done is better than perfect"とはいうけど</h4>
</div>
# Done is MURI !

---
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="だから"  -->
<div class="north span-100 headline">
<h4>考えずに生きていける個人開発にしよう</h4>
</div>
<div class="west span-100">
![Image](./assets/md/assets/usingtool.png)
</div>

---
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="神託"  -->
<div class="north span-100 headline">
<h2>神託</h2>
</div>
<div class="west span-100">
<h2>Prettierとlintを信じよ！</h2>
</div>


---
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="神の導入"  -->
<div class="north span-100 headline">
<h3>神を導入する</h3>
</div>
```
$ yarn add --dev eslint eslint-config-prettier 
  eslint-plugin-prettier prettier prettier-eslint-cli
```

---
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="神を動かす"  -->
<div class="north span-100 headline">
<h3>神の社を建立する</h3>
</div>
```
"scripts": {
+ "format": "prettier-eslint --write './app/**/*.{js,vue}' && prettier-eslint --write './functions/*.{js,vue}'",
+ "lint": "eslint --ext .js,.vue --ignore-path .gitignore ."
}
```

---
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="神の御技"  -->
<div class="north span-100 headline">
<h3>神の御技を拝観する</h3>
</div>
```
// CIで回すと尚良い
$ yarn format && yarn lint
```

---
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="結果"  -->
<div class="north span-100 headline">
<h2>😇</h2>
</div>
```
No problems have been detected in the workspace so far.
```

---
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="おまけ1"  -->
<div class="north span-100 headline">
<h4>おまけ1:定数宣言をpluginにまとめる</h4>
</div>
![Image](./assets/md/assets/plugin.png)

---
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="おまけ2"  -->
<div class="north span-100 headline">
<h4>おまけ2:カラーパレットはscssにまとめる</h4>
</div>
<div class="south span-100">
![Image](./assets/md/assets/scss.png)
</div>

---
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="まとめ"  -->
<div class="north span-100 headline">
<h4>本日のまとめ</h4>
</div>
<div class="west span-65">
- 個人開発は無思考でいこう <br>
- 規約とDevOpsを導入しよう <br>
- 定数とか色も使いまわそう <br>
- MBPが欲しい・・・ <br>
- 技術書典6よろしくね！
</div>
<div class="east span-35">
![Image](./assets/md/assets/qrcode.png)
</div>

---
<!-- .slide: data-background="#00BF81" -->

<!-- .slide:  data-menu-title="END"  -->
<div class="west span-100 text-white startend">
<span style="font-size: 3rem">良い無思考型個人開発ライフを！</span>
</div>