## Service UUID 0000fe95-0000-1000-8000-00805f9b34fb

**ID**: 0000fe95-0000-1000-8000-00805f9b34fb-0x12c1fab9560  
**Type**: Primary

### Characteristics:

| Характеристика                       | Режим                           |
|--------------------------------------|---------------------------------|
| 00000004-0000-1000-8000-00805f9b34fb | readonly                        |
| 00000010-0000-1000-8000-00805f9b34fb | Write Without Response, Notify  |
| 00000017-0000-1000-8000-00805f9b34fb | Write , Notify                  |
| 00000018-0000-1000-8000-00805f9b34fb | Write Without Response , Notify |
| 00000019-0000-1000-8000-00805f9b34fb | Write Without Response , Notify |
| 0000001a-0000-1000-8000-00805f9b34fb | Write Without Response , Notify |
| 0000001b-0000-1000-8000-00805f9b34fb | Write Without Response , Notify |
| 0000001c-0000-1000-8000-00805f9b34fb | Write Without Response , Notify |

## Service UUID 0000180a-0000-1000-8000-00805f9b34fb

#### Device Information Service - Информация об устройстве

**ID**:   
**Type**:

### Characteristics:

| Характеристика                       | Описание                                                  | Пример данных  | Режим |
|--------------------------------------|-----------------------------------------------------------|----------------|-------|
| 00002a24-0000-1000-8000-00805f9b34fb | Model Number String - номер модели                        | LYWSD03MMC     |       |
| 00002a26-0000-1000-8000-00805f9b34fb | Firmware Revision String - версия прошивки                | 2.1.1_0159     |       |
| 00002a27-0000-1000-8000-00805f9b34fb | Hardware Revision String -версия аппаратного обеспечения  | B1.4           |       |
| 00002a28-0000-1000-8000-00805f9b34fb | Software Revision String- версия программного обеспечения | 0159           |       |
| 00002a29-0000-1000-8000-00805f9b34fb | Manufacturer Name String -название производителя          | miaomiaoce.com |       |

## Service UUID ebe0ccb0-7a0a-4b0c-8a1a-6ff2997da3a6

#### Device information - Температура, влажность и напряжение батареи

**Type**:Primary

### Characteristics:

| Характеристика                       | Описание                                                                                        | Пример данных                                                           | Режим        |
|--------------------------------------|-------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|--------------|
| ebe0ccb7-7a0a-4b0c-8a1a-6ff2997da3a6 | Метка времени                                                                                   |                                                                         | Read, Write  |
| ebe0ccbb-7a0a-4b0c-8a1a-6ff2997da3a6 | Данные за последний час                                                                         | id, timestamp, maxTemperature, minTemperature, maxHumidity, minHumidity | Read         |
| ebe0ccba-7a0a-4b0c-8a1a-6ff2997da3a6 | Получить или установить первую запись в истории                                                 |                                                                         | Read, Write  |
| ebe0ccb9-7a0a-4b0c-8a1a-6ff2997da3a6 | Получите последнюю рассчитанную запись за час и следующую, не рассчитанную с момента распаковки |                                                                         | Read         |
| ebe0ccbc-7a0a-4b0c-8a1a-6ff2997da3a6 | Получите массив записей истории, начиная с шага                                                 |                                                                         | Notify       |
| ebe0ccbe-7a0a-4b0c-8a1a-6ff2997da3a6 | Считывание или запись температуры                                                               | 0x00 - F, 0x01 - C                                                      | Read, Write  |
| ebe0ccc1-7a0a-4b0c-8a1a-6ff2997da3a6 | Температура, влажность и напряжение батареи                                                     |                                                                         | Read, Notify |
| ebe0ccc4-7a0a-4b0c-8a1a-6ff2997da3a6 | Процент заряда батареи                                                                          | 100                                                                     | Read         |

ebe0ccc8-7a0a-4b0c-8a1a-6ff2997da3a6 | Write | Descriptors uuid 00002901-0000-1000-8000-00805f9b34fb
ebe0ccd1-7a0a-4b0c-8a1a-6ff2997da3a6 | Write | Descriptors uuid 00002901-0000-1000-8000-00805f9b34fb
ebe0ccd7-7a0a-4b0c-8a1a-6ff2997da3a6 | Read, Write | Descriptors uuid 00002901-0000-1000-8000-00805f9b34fb
ebe0ccd8-7a0a-4b0c-8a1a-6ff2997da3a6 | Write | Descriptors uuid 00002901-0000-1000-8000-00805f9b34fb
ebe0ccd9-7a0a-4b0c-8a1a-6ff2997da3a6 | Write, Notify | Descriptors uuid 00002901-0000-1000-8000-00805f9b34fb ,
00002902-0000-1000-8000-00805f9b34fb
ebe0cff1-7a0a-4b0c-8a1a-6ff2997da3a6 | Write, Write | Descriptors uuid 00002901-0000-1000-8000-00805f9b34fb

service 8edffff0-3d1b-9c37-4623-ad7265f14076
ID:8edffff0-3d1b-9c37-4623-ad7265f14076-0x12c30e2e6f0
UUID:8edffff0-3d1b-9c37-4623-ad7265f14076
Type:Primary
//
Characteristics:

service fafafa00-fafa-fafa-fafa-fafafafafafa
ID: fafafa00-fafa-fafa-fafa-fafafafafafa-0x12c17279100
UUID: fafafa00-fafa-fafa-fafa-fafafafafafa
Type:Primary
//
Characteristics:

service 00010203-0405-0607-0809-0a0b0c0d1912


