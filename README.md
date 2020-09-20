# STM32F401-HelloWorld
Training for new team member

[Hướng dẫn fork và pull request](https://github.com/4Yubox-oversite/STM32F401-HelloWorld/blob/master/H%C6%B0%E1%BB%9Bng%20d%E1%BA%ABn%20fork%20v%C3%A0%20pull%20request)

- [ ] [Cài đặt Github Desktop](https://github.com/4Yubox-oversite/STM32F401-HelloWorld/blob/master/C%C3%A0i%20%C4%91%E1%BA%B7t%20Github%20Desktop)
- [x] [Cài đặt IAR](https://github.com/4Yubox-oversite/STM32F401-HelloWorld/blob/master/C%C3%A0i%20%C4%91%E1%BA%B7t%20IAR)
- [x] Cài đặt STM32CubeMX
- [x] Cài đặt Notepad++ với plugin Astyle
- [x] Tạo tạo project hello world
Code helo world giao tiếp uart vs máy tính dùng Tera Team để xem:
Code đã test
 while (1)
  {
    char str[] = "hello world\n";
      HAL_UART_Transmit(&huart1,(uint8_t *)str,sizeof(str),100);
      HAL_Delay(1000);
  }
