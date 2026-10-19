<div align="center"> # 🌐 Plataformas de Hardware para IoT</div>
Guia prático e coleção de códigos para quem quer estudar e criar projetos de IoT com microcontroladores e microprocessadores.
## 📋 Sobre o Projeto

Este repositório reúne materiais de estudo, circuitos de exemplo e exemplos práticos sobre as principais plataformas de hardware para Internet das Coisas (IoT). Serve como consulta para estudantes, entusiastas e engenheiros que estão criando soluções conectadas.

---

### Visão geral

| Hardware | Tipo | Conectividade | Consumo | Dificuldade | Aplicações típicas |
|---|---|---|---|---|---|
| **ESP32** | Microcontrolador | Wi-Fi, Bluetooth LE | 🔋🔋 | ⭐⭐ | Sensores remotos, automação residencial, wearables |
| **ESP8266** | Microcontrolador | Wi-Fi | 🔋🔋 | ⭐⭐ | Telemetria básica, projetos legados de baixo custo |
| **Arduino (Uno/Nano/Mega)** | Microcontrolador | Via shields/módulos | 🔋 | ⭐ | Ensino, prototipagem rápida, controle simples |

> 🔋 = consumo baixo · 🔌 = precisa de alimentação robusta · ⭐ = nível de dificuldade para iniciantes
> Valores qualitativos e aproximados: confirme sempre nos datasheets.

---

### 🟥 ESP32

O "canivete suíço" do IoT moderno: Wi-Fi e Bluetooth LE integrados com excelente custo-benefício.

- ✅ Wi-Fi + BLE nativos (conforme variante: S3, C3, C6…)
- ✅ Suporte a Arduino, ESP-IDF, MicroPython e PlatformIO
- ✅ Comunidade enorme e muitas bibliotecas
- ⚠️ Consumo ativo maior que MCUs focados em BLE
- 🎯 **Use quando:** quer um dispositivo Wi-Fi barato, versátil e fácil de programar

### 🟦 Arduino

A porta de entrada para eletrônica e programação embarcada.

- ✅ Curva de aprendizado suave e milhares de tutoriais
- ✅ Ecossistema de shields e sensores
- ⚠️ Placas clássicas (AVR) têm pouca memória e nenhuma conectividade nativa
- 🎯 **Use quando:** está aprendendo, ensinando ou validando uma ideia simples

