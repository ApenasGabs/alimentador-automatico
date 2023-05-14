# alimentador-automatico

## Projeto criado no intuito de reviver um alimentador automatico que parou de funcionar




## Configuracoes 
### use a branch config para fazer a configuracao inicial de hora e data do modulo RTC 
1. Descomente o trecho do codigo  `rtc.adjust(DateTime(F(__DATE__), F(__TIME__)));`
2. Faca upload
3. Comente novamente o `rtc.adjust(DateTime(F(__DATE__), F(__TIME__)));`
4. Ultilize o monitor serial na velocidade 57600 para verificar a data / hora
