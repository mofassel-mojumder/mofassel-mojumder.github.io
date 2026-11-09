# Portfolio live korar guide - GitHub Pages

## Age keno GitHub Pages?

Tomar site ekta static HTML file, kono server dorkar nai. GitHub Pages free-te ei file-ta live kore dey, Shakib-er site-tao evabei live (ppcshakib.github.io). Kono taka lagbe na, kono server maintain korte hobe na.

## Zip-er vitore ki ache

- `index.html` - tomar portfolio, fast version (age chilo 1.45 MB, ekhon 384 KB)
- `og-image.jpg` - Facebook / LinkedIn share-er chobi, 1200x630, ami baniye diyechi
- `images/` - 18-ta chobi: logo, tomar photo, 6-ta testimonial photo, 10-ta dashboard screenshot
- Ei file-ta (`README-GITHUB-PAGES.md`) - sudhu guide, site-er ongsho na, chaile GitHub-e upload na korleo cholbe

## Age ekta safety kotha

Tomar ager file `mofassel-lime.html` ami touch kori nai, oita tomar kachei ache. Ei zip-er file-gulo alada folder-e ache, tai purano file-er sathe mishbe na.

## Step 1: GitHub-e notun repo banao

1. GitHub.com-e jao, upore dan dike `+` chapo, tarpor `New repository` chapo.
2. Repository name lekho: `hellomofassel.github.io`
   - Ei nam-ta dile site-er address hobe `https://hellomofassel.github.io/`
   - Onno nam dileo cholbe, kintu ei nam-ta sobcheye sohoj.
3. `Public` select koro. Private repo-te free Pages cholbe na.
4. `Add a README file` tick dio NA. Khali repo banao.
5. `Create repository` chapo.

## Step 2: Zip theke file-gulo GitHub-e tolo

Sohoj rasta, browser diye:

1. Zip-ta extract koro. Vitore `mofassel-portfolio-live` nam-e ekta folder pabe.
2. Oi folder-ta kholo. Vitore dekhbe `index.html`, `og-image.jpg`, `images` folder.
3. GitHub-er notun repo page-e `Add file` chapo, tarpor `Upload files` chapo.
4. `index.html`, `og-image.jpg`, ar `images` folder-ta eksathe drag kore dao.
   - SABDAN: bahirer folder-ta (`mofassel-portfolio-live`) drag koro NA. Vitoreer jinish-gulo drag koro. Nahole site khulbe na, karon `index.html` root-e thakte hobe, folder-er vitore na.
5. Niche `Commit changes` chapo.

VS Code diye korte chaile (tumi GAIP-er somoy jevabe push korecho):

1. Repo-ta clone koro.
2. `index.html`, `og-image.jpg`, `images` folder copy kore repo folder-e paste koro.
3. Commit koro, tarpor push koro.

## Step 3: Pages on koro

1. Repo page-e `Settings` chapo.
2. Bam dike `Pages` chapo.
3. `Build and deployment` - `Source`-e `Deploy from a branch` thakbe.
4. Branch-e `main` select koro, folder-e `/ (root)` select koro, `Save` chapo.
5. 1-2 minute wait koro. Upor-e sobuj lekha asbe: `Your site is live at https://hellomofassel.github.io/`
6. Oi link-e click koro.

## Step 4: Live site-ta check koro

Ekta ekta kore check koro:

1. Hero photo ar nam thik ache kina.
2. Services-e price £499 / £799 dekhacche kina, currency change korle $640-ero moto dekhacche kina.
3. Results-e gallery slide change hocche kina, dashboard chobi asche kina.
4. Case studies 3-ta, testimonial 6-ta dekhacche kina.
5. Contact form-e nam, email, service diye `Send my details` chaple thank-you asche kina. Form-ta Sheet-e jabe, kintu Sheet-e gelo kina pore check koro.
6. `Book a call` chaple Zcal khulche kina.
7. Form-er niche `Message me on WhatsApp` button-e click korle WhatsApp khulche kina.
8. Facebook / LinkedIn-e link share korle og-image asche kina. Prothombar na asle 10 minute pore abar try koro, Facebook cache derite update hoy.

Kono ekta check fail korle amake exact ki dekhacche seta screenshot diye pathao, ami thik kore dibo.

## Pore, jokhon Mofassel.co connect korte chao

Ekhon-ei korte hobe na. Site age `hellomofassel.github.io`-te live hok, tarpor:

1. Repo `Settings` -> `Pages` -> `Custom domain`-e `mofassel.co` lekho, `Save` chapo.
2. Tomar domain jekhan theke kena, okhane DNS-e CNAME dite hobe. Registrar-er nam amake bolo, ami exact step bole dibo.
3. Tarpor `Enforce HTTPS` tick dao.

## Speed: age keno slow chilo, ekhon ki bodleche

Age slow chilo karon:

- Pura site ekta file chilo, 1.45 MB. 19-ta chobi base64 hoye HTML-er vitore dhokano chilo.
- Browser prothom paint-er agei sob chobi download ar decode korto, gallery-r 10-ta dashboard-o ekbare load hoto.
- Repeat visit-eo kono caching subidha chilo na, karon chobi alada file chilo na.

Ekhon:

- `index.html` 384 KB, mane 74% choto.
- Chobi alada file, mot 725 KB, kintu prothome sudhu hero photo (55 KB) ar logo (16 KB) load hoy.
- Gallery-te sudhu prothom slide-ta age load hoy, porer slide-ta slide change korle load hoy. Thumbnail-gulo lazy.
- Testimonial photo sudhu oi tab-e click korle load hoy.
- Repeat visit-e browser chobi cache theke ney, abar download kore na.
- Hero photo preload kora ache, tai sobcheye boro chobi-ta age ase.

Amar check: local server-e 18-ta chobi-r sobgulo 200 OK, JS syntax 4-ta script-ei pass, og-image chokhe dekhe verify kora.

## Ekhono ja baki (SEO-r age)

- Dashboard screenshot ekhono Jul-Aug 2025-er. 2026-er notun screenshot pele bodle dio.
- $4M+, 60+ clients, 12400+ leads, ei number-gulo publish-er age ekbar miliye nio.
- Erpor amra SEO niye kaj korbo: Google Search Console, sitemap, ar Mofassel.co connect.
