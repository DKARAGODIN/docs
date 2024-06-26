# Монтирование бакетов в контейнер

Монтирование бакетов позволяет обращаться к бакетам через интерфейс файловой системы. В настройках ревизии контейнера пользователь может указать путь монтирования или несколько. Директория, к которой смонтируется бакет, будет доступна по указанному пути. По этому пути нельзя размещать ничего, кроме пустой директории, иначе при инициализации контейнера может возникнуть ошибка, и монтированные бакеты будут недоступны.

Смонтировать можно весь бакет или [папку](../../storage/concepts/object#folder).

По пути `/run/storage_sync_socket` размещается Unix-сокет. Чтобы не произошла потеря информации при чтении данных из бакета или их записи в него:
* по пути Unix-сокета нельзя ничего размещать;
* нельзя читать из Unix-сокета и писать в него.


{% include [roles-for-bucket-mounting](../../_includes/functions/roles-for-bucket-mounting.md) %}

## См. также {#see-also}

* [Монтировать бакеты в контейнер](../operations/mount-bucket.md)
* [Монтировать бакеты в функцию](../../functions/operations/function/mount-bucket.md)
