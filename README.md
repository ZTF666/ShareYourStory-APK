# Share Your Story - APK

<div align="center">
<p>This is the code for the mobile app version of my web app  </p>

[Share Your Story](https://shareyour-story.web.app/) .

<p>This mobile app is ⚠️NOTHING BUT A WEBVIWER⚠️ that renders the website in a more mobile friendly way . </p>
</div>

<div align="center">
<img src="/scr/main.png"  >

</div>

## How does it work :

<div align="center">
<p>Nothing fancy , this uses a webview that loads the url of the webapp and simply display its content into a more friendly way that just opening it in a browser</p>
</div>

## Code :

```java

        webview = findViewById(R.id.webview);
        // This block is to allow url redirection inside the webview
        webview.setWebViewClient(new WebViewClient() {
            @Override
            public boolean shouldOverrideUrlLoading(WebView view, String url) {
                return false;
            }
        });
        WebSettings webSettings=webview.getSettings();
        // Enabling JS ofc
        webSettings.setJavaScriptEnabled(true);
        webview.loadUrl("https://shareyour-story.web.app/");

```

## Downsides :

<div align="center">
<p>Im no fancy android developer, so i didn't think about opening new windows inside the webview ...</p>
<p>so when you use IMGUR to upload a picture to get its link to use in the app to make a post , once the window is open you cant go back 😅😅 </p>
</div>
<div align="center">
<img src="/scr/Lol.gif"  >

</div>

## Contact

```
you can contact me at ZTF666@protonmail.ch

```

<div align="center">

<table>
  <tr>
    <td align="center"><a href="https://ztfportfolio.web.app/" target='_blank'><img src="https://avatars1.githubusercontent.com/u/32502988?v=4" width="100px;" alt=""/><br /><sub><b>ZTF666</b></sub></a></td>
  </tr>
</table>

</div>

## License

<div align="center">

**💎Share Your Story - APK💎** released under the [MIT](LICENSE) License.
<br><br>
<strong><p>Made with 💘 ZTF666 - N.EA</p> </strong>

Illustrations by the cool people at : [Pixeltrue](https://www.pixeltrue.com/free-illustrations)
Illustrations by the cool people at : [FreePik](https://www.freepik.com/vectors/people)
Backgrounds by the nice Matt at : [SVG Background](https://www.svgbackgrounds.com/)

</div>
