
# <p align="center">Chisel معرفی و آموزش تانل</p>
  
همینطور که میدونید، اگه بخوایم از CDN کلادفلر یا مشابه اون استفاده کنیم و سرورمون رو پشت CDN مخفی کنیم، فقط می‌تونیم از ترنزمیشن های Ws و gRPC استفاده کنیم. دلیلشم اینه که در پلن رایگان کلادفلر، انتقال ترافیک‌های TCP و UDP ممکن نیست و برای این کار نیاز به تهیه پلن پریمیوم داریم. 
توی این آموزش یاد میگیرید که چطوری با استفاده از ابزار Chisel،یک تانل بین 2 سرور ایجاد کنید و ترافیک‌های TCP و UDP را به Ws تبدیل کنید. به عبارت دیگه،نیازی به خرید پلن پریمیوم برای انتقال ترافیک‌های TCP و UDP نیست:)
