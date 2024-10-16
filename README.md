# Ponderada de Arduino

## **Parte 1**

### Blink:

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

## **Parte 2**

### TinkerCad:

[Projeto](https://www.tinkercad.com/things/hRPRlcwMMXG/editel?sharecode=SGhSdjqDoCzESckULB_oFYcz2jFtmdcwp4eqvEl_VWg)

**Código do Projeto:**

```
// C++ code
//
#define R 6
#define G 4
#define B 5
void setup()
{
  pinMode(3, OUTPUT);
  pinMode(R, OUTPUT);
  pinMode(G, OUTPUT);
  pinMode(B, OUTPUT);
}

void loop()
{
  digitalWrite(3, HIGH);
  delay(1000);
  digitalWrite(3, LOW);
  delay(1000);
  analogWrite(R, random(255));
  analogWrite(G, random(255));
  analogWrite(B, random(255));
  delay(200);
}
```
