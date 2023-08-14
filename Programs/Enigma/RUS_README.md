Энигма, это программа, которая эмулирует работу переносной шифровальной машинки, использовавшейся для шифрования и расшифрования секретных сообщений
----------------------------------------------------------------------------------------------------------------------------------------------------
Вся ее прелесть была в том, что при шифровании она меняла [один и тот же символ на разные](https://github.com/SixthCrowned/Personal-Repository/blob/main/Enigma/ScreenShot2.png), из-за чего самые распространенные методы расшифрования уже теряли свою актуальность<br>
Что и сподвигло меня на непреодолимое желание воссоздать ее работающую копию :)<br><br>
Самым трудным было организовать процесс "вращения" роторов и обратное дешифрование сообщения. Код ужасен, в плане написания, он работает, некрасив, но моей основной целью было не совершенствование навыков написания кода, а достижение создания работающего прототипа<br>
Я сделал возможным выставление отражателя и ротов на разные позиции по желанию, после чего нужно было лишь их "зафиксировать", вписать фразу и получить [зашифрованное сообщение](https://github.com/SixthCrowned/Personal-Repository/blob/main/Enigma/ScreenShot3.png)<br>
При дешифровании полученное сообщение необходимо внести в поле ввода, выставить позиции роторов на те, что были при шифровании этого сообщения, и на выходе получится [начальное сообщение](https://github.com/SixthCrowned/Personal-Repository/blob/main/Enigma/ScreenShot4.png)<br>