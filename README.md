# Вторая лабораторная

#### Небходимые ПО
* Android Studio

#### Используемые технологии
* Java
* XML
* Gradle

#### Описание работы
В основном активити у нас находятся 1 кнопка "Перейти к анимации Tween" и textView "привет".
По нажатию на кнпку переводится в другое активити, где распологоается элемент imageView который двигается по дуге  и это движение евляется бесконечным, и с разной переодичнастью меняет свой размер и прозрачность
 #### В первом активити анимация была написана в виде кода, без использования сторонних библиотек, используя такие свойства как:

* .setAlpha
* .alpha
* .setDuration
* .setStartDelay

#### Во втором активити анимация была написана в XML c использованием Tween-анимации. Использовались такие элементы как:

* scale
* rotate
* alpha
* translate
