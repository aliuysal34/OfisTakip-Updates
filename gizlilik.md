# Ofis Takip Giriş Yardımcısı — Gizlilik Politikası

*Yürürlük tarihi: 3 Ekim 2026*

Bu politika, Microsoft Edge için yayımlanan **Ofis Takip Giriş Yardımcısı** eklentisinin bilgileri nasıl kullandığını açıklar. Eklenti, mali müşavirlik bürolarının kendi bilgisayarlarında çalışan Ofis Takip programının tamamlayıcısıdır.

## Hangi bilgiler kullanılır

Kullanıcı Ofis Takip programında bir firma için “Kuruma git” dediğinde, programda o firma için kayıtlı resmî kurum giriş bilgileri (kullanıcı adı / T.C. kimlik no / vergi kimlik no, şifre, ek kullanıcı numarası gibi) kullanıcının kendi programından eklentiye verilir. Eklenti bu bilgileri yalnızca açılan resmî kurum giriş sayfasındaki formu doldurmak için kullanır.

## Bilgiler nerede ve ne kadar süre tutulur

- Bilgiler yalnızca kullanıcının bilgisayarında, tarayıcının oturum belleğinde (`chrome.storage.session`) ve yalnızca açılan sekme için tutulur; diske yazılmaz.
- En fazla 2 dakika sonra ya da sekme kapatılınca silinir.

## Paylaşım

- Hiçbir bilgi geliştiriciye, Microsoft'a ya da üçüncü bir kişiye gönderilmez, satılmaz, paylaşılmaz.
- Eklentinin kendi sunucusu yoktur; eklenti internete kendisi bağlanmaz. Bilgiler yalnızca kullanıcının kendi Ofis Takip programından gelir ve yalnızca kullanıcının açtığı resmî kurum sayfasının formuna yazılır.
- Analiz, reklam ya da izleme yapılmaz; çerez kullanılmaz.

## Eklentinin çalıştığı sayfalar

- Ofis Takip program sayfası. Program bürodan büroya farklı adreste çalıştığı için eklenti sayfayı özel bir etiketle tanır; diğer sayfalarda hiçbir şey yapmaz, içeriklerini okumaz.
- Resmî kurum giriş sayfaları: dijital.gib.gov.tr, ebildirge.sgk.gov.tr, uyg.sgk.gov.tr, giris.turkiye.gov.tr, ebirlik.turmob.org.tr — yalnızca Ofis Takip'ten “Kuruma git” ile açılan sekmede.

## Güvenlik kodu

Resmî kurum sayfalarındaki güvenlik kodunu (captcha) eklenti çözmez; kodu her zaman kullanıcı kendisi girer.

## İletişim

Sorularınız için: aliuysal34@gmail.com

Bu politika değişirse güncel hâli bu sayfada yayımlanır.

---

# Ofis Takip Login Assistant — Privacy Policy (English)

*Effective date: 3 October 2026*

The **Ofis Takip Login Assistant** extension is a companion to the Ofis Takip application that accounting firms run on their own computers.

- **What is used:** when the user chooses “Kuruma git” (go to institution) for a client in Ofis Takip, the login fields saved for that client in the user's own Ofis Takip application (user name / Turkish ID or tax number, password, additional user number) are passed to the extension and used only to fill the login form of the official government page opened in a new tab.
- **Storage:** kept only on the user's computer, in the browser's session memory (`chrome.storage.session`), for that tab only, for at most 2 minutes; never written to disk.
- **Sharing:** nothing is sent to the developer, Microsoft or any third party; no data is sold or shared. The extension has no server and makes no network requests of its own. No analytics, advertising, tracking or cookies.
- **Where it runs:** the Ofis Takip application page (recognised by a special tag; it does nothing on other pages) and the official login pages dijital.gib.gov.tr, ebildirge.sgk.gov.tr, uyg.sgk.gov.tr, giris.turkiye.gov.tr, ebirlik.turmob.org.tr — only in a tab opened through “Kuruma git”.
- **Security codes:** the extension never solves CAPTCHA / security codes; the user always types them.
- **Contact:** aliuysal34@gmail.com
