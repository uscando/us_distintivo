# us_distintivo
Distintivo per fbi e lspd 

Modificare la riga 12 del server.lua

--'TriggerClientEvent('dopeNotify2:Alert', source, "LSPD", "Stai mostrando il distintivo", 2500, 'warning') -- Notifica da cambiare con il vostro notify'

Nome item (dist)


database

USE `essentialmode`;

INSERT INTO `items` (`name`, `label`, `weight`, `rare`, `can_remove`) VALUES
	('dist', 'Distintivo', -1, 0, 1)
;
