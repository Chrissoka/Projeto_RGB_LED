# Projeto_RGB_LED
**Meu primeiro projeto arduino - tinkercard**

## IMAGEM DO CIRCUITO
![projeto_rgb_led_imagem](https://user-images.githubusercontent.com/90460886/192655961-8614c750-39ee-4408-9e8d-9b4f15d0f43e.png)

## CÓDIGO
**C++**

```
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
}

void loop()
{
  analogWrite(13, 255);
  analogWrite(12, 0);
  analogWrite(11, 0);
  delay(1000);
  analogWrite(13, 255);
  analogWrite(12, 255);
  analogWrite(11, 102);
  delay(1000);
}
```
