# シーンの追加方法
1. `scenes/SceneTemplate.js`を`scenes/シーン名.js`としてコピーする
2. `シーン名.js`を開き`SceneName`をシーン名に置き換える
3. `index.html`内に作成したシーンをimportし、scene配列内にシーン名を追加する

# シーンの基本操作
 * **既存のシーンを終了して新しいシーンを呼び出し**
    `this.scene.start("シーン名")`
 * **既存のシーンに重ねて別のシーンを呼び出し**
    `this.scene.launch("シーン名")`
 * **シーンを指定して中断**
    `this.scene.pause("シーン名")`
 * **シーンを指定して再開**
    `this.scene.resume("シーン名")`
 * **シーンを指定して終了**
    `this.scene.stop("シーン名")`
