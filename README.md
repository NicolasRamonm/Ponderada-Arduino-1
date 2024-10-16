# Ponderada de Arduino

## Blink:

**Código para o blink, 5 segundos ligado e 1 desligado**

```
void setup() {
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop() {
  digitalWrite(LED_BUILTIN, HIGH);  
  delay(5000);                      
  digitalWrite(LED_BUILTIN, LOW);   
  delay(1000);                      
}

```
<img src="image (6).png" alt="Blink">

[**Código funcionando**](https://youtu.be/5nNRW5TTODQ)
