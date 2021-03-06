# service-worker
Experiments with service-worker

# To start project

* ```npm i```  
* ```npm run dev```

### Service worker

* не имеет доступа к DOM 
* работает в отдельном потоке от основного JavaScript 
* синхронные XHR и localStorage, не могут быть использованы в SW???
* SW запускаются только по HTTPS из соображений безопасности
* не работает localStorage
* можно использовать IndexedDB  

### Service worker будет следовать следующему жизненному циклу:

* Загрузка
* Установка
* Активация

### Useful links

* spec: https://www.w3.org/TR/service-workers-1
* https://developers.google.com/web/ilt/pwa/tools-for-pwa-developers#offline
* https://github.com/jakearchibald/trained-to-thrill
* https://www.youtube.com/watch?v=4uQMl7mFB6g
* https://github.com/GoogleChrome/samples/tree/gh-pages/service-worker
* https://serviceworke.rs

background sync
* spec: https://wicg.github.io/BackgroundSync/spec/
* https://www.twilio.com/blog/2017/02/send-messages-when-youre-back-online-with-service-workers-and-background-sync.html
* https://ponyfoo.com/articles/backgroundsync
* https://stackoverflow.com/questions/41798009/pass-custom-data-to-service-worker-sync

push-notifications
* spec: https://www.w3.org/TR/push-api/
* spec: https://notifications.spec.whatwg.org/
* https://peter-gribanov.github.io/serviceworker/

postMessages and MessageChannel
* https://ponyfoo.com/articles/serviceworker-messagechannel-postmessage
