# BKIT-lab7
in lab 7 we will discuss about LCD Touch screen

## Configuration: IMGs ARE INCLUDED IN GIT
### Clock Source Configuration
1. Pinout & Configuration -> System Core -> RCC -> HSE: Crystal/Ceramic Resonator
2. Pinout & Configuration -> System Core -> SYS -> Debug: Serial Wire
3. Clock Configuration -> HCLK (MHz): 168, APB1 Prescaler: /4, APB2 Prescaler: /4

### Timer Configuration
4. Pinout & Configuration -> TIM2 -> Clock Source: Internal Clock -> NVIC Settings -> TIM2 global interupt: <tick enable>, Parameter Settings -> Prescaler: 8400-1, Counter Period: 10-1
mathematical formular: 
$$
f = \frac{F}{1 + \text{pre}} \times (1 + \text{period})
$$

<img width="1470" alt="image" src="https://github.com/user-attachments/assets/4c640649-369e-4aa0-8078-4852789ad9ef">

