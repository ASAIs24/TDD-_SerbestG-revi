Bu proje, Selenium ve BeautifulSoup kullanarak Trendyol'daki ürün sayfasından ürün detaylarını ve kullanıcı yorumlarını otomatik olarak çeken bir Python betiği içerir. Çekilen veriler daha sonra bir Excel dosyasına kaydedilir.

KURULUM

Bu projeyi yerel ortamınıza kurmak için aşağıdaki komutları terminal veya komut istemcisinde çalıştırarak gerekli kütüphaneleri kurabilirsiniz.

1. pip install selenium
2. pip install beautifulsoup4
3. pip install pandas
 Bu komutlar ile gerekli kütüphaneleri kurabilirsiniz.

ÇALIŞTIRMA

1. Chromedriver'ı veya GeckoDriver'ı indirin.
 
Sürüm Öğrenme: 
Chrome: Menü > Yardım > Google Chrome Hakkında.
Firefox: Menü > Yardım > Firefox Hakkında.

Driver İndirme:
ChromeDriver:https:  //developer.chrome.com/docs/chromedriver/downloads
GeckoDriver:https:  //github.com/mozilla/geckodriver/releases
 
2.ChromeDriver'ın veya GeckoDriver'ın bulunduğu klasörün yolunu şu şekilde belirtin.

driver = webdriver.Chrome(executable_path='/path/to/chromedriver')

driver = webdriver.Firefox(executable_path='/path/to/geckodriver')


3. Yorumlarını çekmek istediğiniz Trendyol ürün sayfasının URL'sini url değişkenine girin:

url = 'https://www.trendyol.com/...'


Uygulamanın çalışması için gerekli adımlar tamamlanmıştır, belirtilen ürün sayfasını ziyaret eder, tüm yorumları çeker ve bir Excel dosyasına kaydeder.
