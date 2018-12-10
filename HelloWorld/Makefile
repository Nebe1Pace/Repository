# name of your application(имя приложения)
APPLICATION = hello-world

# If no BOARD is found in the environment, use this default:(Название платы, для которой происходит сборка проекта)
BOARD=stm32f0discovery 

# This has to be the absolute path to the RIOT base directory:(абсолютный путь к базовому каталогу RIOT)
RIOTBASE ?= $(CURDIR)/../..

# Comment this out to disable code in RIOT that does safety checking(Прокомментируйте это, чтобы отключить код в RIOT, который выполняет проверку безопасности)
# which is not needed in a production environment but helps in the(который не требуется в производственной среде, но помогает в)
# development process:(процессе разработки)
DEVELHELP ?= 1

# Change this to 0 show compiler invocation lines by default:(Измените это значение на 0, показывая строки вызова компилятора по умолчанию:)
QUIET ?= 1

include $(RIOTBASE)/Makefile.include
