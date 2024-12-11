## مقدمة عن Jodija

مع تطور تقنية Flutter  واصبح لدينا منصات متعددة كان لازاما ان تظهر لدينا مشكلة تعدد الواجهات و تعدد الحلول وخصوصا مع المشاريع الكبيرة تخيل معي انك تقوم بتصميم مشروع تجاري مكون من لوحة التحكم و موقع و تطبيق للمستخدم و تطبيق للبائع وذلك طبقا لطلب المستخدم وهذا تلطبيق قابل للتوسع لذا يجب عليك ان تعدد ال modules حتى لا يكبر حجم التطبيق و تتعدد مشاكلة و ايضا يدخل معك في الاعتبار تعدد الواجهاتو تغير احجام شاشات الاجهزة للواجهة الواحدة و كذلك عند الاتصال مع ال api  و ال firebase  وغيرها من الخوادم ليتم ربط اجزاء التطبيق  كل هذه المشكلات كانت سبب للعمل على   Jodija 
 ما هي Jodja هي عبارة عن مكتبتين تشكلان اطار عمل كل واحدة منهما لها دور  في ادارة مسار البينات من الواجهات الى المخدمات  . المكتبتان هما 
 1-مكتبة Jodija data source : وهي تتحكم في ادارة مسhر البيانت اللي نستقبلها او نرسلها للخوادم عن طريق Api او اي منصة خوادم مثل Firebase  و تقوم بمهم اعادة تشكيل البيانات مبا يتوافق مع ال bussenes logic ليتم عرضها على المستخدم في حالة اذا كانت البيانات قادمة من السيرفر او تشكيلها على صيغة Json في حالة ارسالها الى الخوادم 
 2-مكتبة Jodija data view: 

## Features

TODO: List what your package can do. Maybe include images, gifs, or videos.

## Getting started

TODO: List prerequisites and provide or point to information on how to
start using the package.

## Usage

TODO: Include short and useful examples for package users. Add longer examples
to `/example` folder.

```dart
const like = 'sample';
```

## Additional information

TODO: Tell users more about the package: where to find more information, how to
contribute to the package, how to file issues, what response they can expect
from the package authors, and more.
