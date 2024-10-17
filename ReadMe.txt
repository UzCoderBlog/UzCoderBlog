Ссылка на demo
https://dev.stack.jimmycai.com
https://demo.stack.jimmycai.com

-------------------------------------------------
WiKi
https://stack.jimmycai.com/config/widgets#widgets
https://themes.gohugo.io/themes/hugo-theme-stack/


-------------------------------------------------
Submodle:

1.Проверьте наличие подмодуля: Выполните команду, чтобы посмотреть, есть ли уже добавленный подмодуль:

git submodule

Если hugo-theme-stack уже добавлен как подмодуль, вам может не понадобиться добавлять его снова.

2.Удалите существующий подмодуль (если он не нужен): Если подмодуль уже добавлен и вы хотите его удалить, выполните следующие команды:

git submodule deinit -f themes/hugo-theme-stack
git rm -f themes/hugo-theme-stack
git commit -m "Remove existing submodule"

git submodule add https://github.com/CaiJimmy/hugo-theme-stack.git themes/hugo-theme-stack 

3.Добавьте подмодуль снова: После удаления подмодуля вы можете повторно добавить его:

git submodule add https://github.com/CaiJimmy/hugo-theme-stack.git themes/hugo-theme-stack

Если hugo-theme-stack существует как обычная папка, и вы хотите ее заменить подмодулем, сначала удалите эту папку:

rm -rf themes/hugo-theme-stack

-------------------------------------------------
Мои репозитории:
https://github.com/UzCoderBlog/UzCoder-Blog.git

echo "# UzCoder-Blog" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/uzcoderblog/uzcoderblog.github.io.git
git push -u origin main

git remote add origin https://github.com/uzcoderblog/uzcoderblog.github.io.git
git branch -M main
git push -u origin main

-------------------------------------------------

<!-- Google Analytics -->
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-PG16D4GTLK"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-PG16D4GTLK');
</script>

<!-- ----------------------------------------------------------------------------------------------------------------------------- -->

<!-- Yandex.Metrika counter -->
<script type="text/javascript" >
   (function(m,e,t,r,i,k,a){m[i]=m[i]||function(){(m[i].a=m[i].a||[]).push(arguments)};
   m[i].l=1*new Date();
   for (var j = 0; j < document.scripts.length; j++) {if (document.scripts[j].src === r) { return; }}
   k=e.createElement(t),a=e.getElementsByTagName(t)[0],k.async=1,k.src=r,a.parentNode.insertBefore(k,a)})
   (window, document, "script", "https://mc.yandex.ru/metrika/tag.js", "ym");

   ym(98658989, "init", {
        clickmap:true,
        trackLinks:true,
        accurateTrackBounce:true
   });
</script>
<noscript><div><img src="https://mc.yandex.ru/watch/98658989" style="position:absolute; left:-9999px;" alt="" /></div></noscript>
<!-- /Yandex.Metrika counter -->

