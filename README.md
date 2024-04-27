# item_modifier-modify_contents
item_modifierの1項目であるmodify_contentsのサンプルになります。

詳しくはブログ記事『[【マイクラ】modify_contentsで格納物にitem_modifier付与【item_modifier】](https://natsumake.com/item_modifier-modify_contents/)』を参考にしてください。

<h3>概要</h3>
格納物に対してitem_modifierを適用させられます。<br>
具体的にはcontainer, bundle_contents, charged_projectilesを持つアイテムが対象になります。

<h3>使い方</h3>

データパック導入後、ワールドに入り```/reload```と入力し実行してください。

クロスボウ、バンドル、チェストが与えられ、バンドルとチェストにはアイテムが既に格納されています。

それぞれに以下のコマンドを実行することで、格納しているアイテムの名前を変更できます。

<h4>チェストに対して行うコマンド</h4>

```copy
/item modify entity @s weapon.mainhand sample:container
```

<h4>バンドルに対して行うコマンド</h4>

```copy
/item modify entity @s weapon.mainhand sample:bundle_contents
```

<h4>クロスボウに対して行うコマンド</h4>

```copy
/item modify entity @s weapon.mainhand sample:charged_projectiles
```
