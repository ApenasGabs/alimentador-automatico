# alimentador-automatico

## Projeto criado no intuito de reviver um alimentador automatico que parou de funcionar




### Configuracoes 
use a branch confi para fazer a configuracao inicial de hora e data do modulo RTC 
use o monitor serial para verificar novamente a data/ hora
descomente o rtc.adjust(DateTime(F(__DATE__), F(__TIME__))); 
 faca upload
 comente novamente o rtc.adjust(DateTime(F(__DATE__), F(__TIME__))); 
 use o monitor serial para verificar novamente a data/ hora
