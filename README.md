**しらたまWPFブラウザへようこそ！**
**Welcome to Siratama WPF Browser!**

しらたまブラウザはWPF及びWebView2の技術を使用したシングルタブブラウザです。


どちらかというと開発者向けであり、実用はお勧めしません。(Youtubeを30分流せるほどには安定していますが私自身コードの全容を把握できていません。)<br>
個人製作のブラウザを探しているなら「InternetStroller Memoria」がおすすめです。私が開発しているオープンソースの軽量ブラウザです。


このプログラムはMicrosoftのWPF向けサンプルに手を加えて動くようにしたものです。<br>
主な変更点は<br>
・対象を.NetCore3.0から.Net6.0-windowsに変更<br>
・主なコマンドを日本語に翻訳<br>
・ビルドエラーの修正<br>
・一応使えるように機能の追加<br>
です。


注意点は<br>
・MicrosoftがサンプルコードにBSDライセンスをかけています。「完全自作ブラウザ」「日本製ブラウザ」とかいうのはやめましょう。<br>
・0.1時点ではWebView2のNugetが古いです。普通に更新すると使えなくなってしまうので対応を検討中です。


ABATBelieverは別にこのコードで何やってもいいですが、**MicrosoftのBSDライセンスは守りましょう**。<br>
なお、コードの質問などはIssueに投げるなりDiscordに相談するなりしていただければ出来る範囲で対応します。<br>
いつかQuitaあたりに解説したいね。


Siratama Browser is a single tab browser using WPF and WebView2 technologies.<br>
It is more for developers and is not recommended for practical use.<br>
If you are looking for a browser for personal use, I recommend "InternetStroller Memoria".<br>


This program is a modified version of Microsoft's WPF sample.<br>
The main changes are<br>
・Changed the target from .NetCore3.0 to .Net6.0-windows<br>
・Translated main commands into Japanese.<br>
・Fixed build errors.<br>
・Added functions to be usable.<br>
The following is a summary of the changes.


Points to note are<br>
・Microsoft has put a BSD license on the sample code. Don't call it a "completely homebrew browser" or "Japanese-made browser".<br>
・Nuget of WebView2 is out of date as of 0.1. We are considering to support it, because it will be unusable if you update it normally.<br>


ABATBeliever is free to do whatever you want with this code, but please abide by Microsoft's BSD license.
