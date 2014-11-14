# meteor-uikit-data

這個 Meteor package 僅提供一個取得 [Uikit Framework](http://getuikit.com) 的雲端中介套件，使用 git submodule 串聯原始 Uikit，並替前端新增靜態的字型檔案。

原則上移植了 Memo64 建構的 bootstrap 套件架構，因此使用方式是透過 meteor-uikit 套件來取用，單獨的用處不大。

The reason this package exists is to provide a workaround for the limitation, that meteor does not allow static assets to be accessed in a build plugin. It is however allowed to 'use' other packages in a plugin and this other package can than provide static assets (which is what this package does).