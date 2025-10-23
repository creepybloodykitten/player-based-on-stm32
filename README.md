# player-based-on-stm32

для работы с sd card по spi:
1)скопировать fatfs_sd h и c, user_diskio.с тоже

2)изменить stm....it файл(systick)

3)изменить в ffconf макрос exfat на 1 и use_find на 1
