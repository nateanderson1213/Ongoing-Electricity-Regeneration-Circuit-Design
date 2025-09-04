# Smart Solar Power Bank with AI Prediction
Work in Progress — Solar power electronics with machine learning

## Objectives
- Design and test a rechargeable solar circuit (TP4056 + LiPo)
- Monitor voltage, current, and charge status on LCD
- Collect solar charging data via ESP32
- Train AI model in Google Colab to predict battery levels
- Explore BLE/WiFi for remote monitoring

## Hardware
- ESP32 Dev Board
- TP4056 Charging Module
- 3.7V LiPo Battery (1000 mAh)
- 6V Solar Panel (200 mA)
- 16x2 I²C LCD
- Breadboard + Jumper Wires
- (Optional) MT3608 Boost Converter (5V output)
  
## Current Progress
- Breadboard prototype (ESP32 + TP4056 + LiPo + solar panel)
- Initial AI model (linear regression in Colab)
- ESP32 voltage/current monitoring
- Data logging to CSV
- Testing boost converter for stable 5V

## Future Improvements
- Improve AI (random forest, neural networks)
- Add BLE for mobile integration
- Design custom PCB
- Build portable case/housing
