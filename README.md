# golang vendoring

dengan melakukan vendoring, kita akan mengunduh semua dependensi / 3rd party kedalam project kita yang akan disimpan didalam subfolder _vendor_

lalu supaya golang melookup ke folder _vendor_ saat melakukan build / run adalah dengan nenambahkan flag `-mod=vendor` saat build / run
