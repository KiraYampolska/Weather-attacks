# Weather-attacks
 -Функція def read_file(path) - зчитує файл csv та перетворює його на табличку, прибирає колонку city, оскільки для аналізу вона не потрібна\n
 -Функція def calculate_max_attacks(df) - виводить місяць, у якому в конкретній області було найбільше тривог (тобто повідомлень з '💥', '📍', '⚠️')\n
 -Функція def month_attack(df) - виводить кількості атак по місяцям, враховуючи всі, а не тільки табличні\n
 -Функція def process_weather_data(df) - виводить кількість повідомлень для конкретної області в залежності від погоди\n
 -Функція def region_temperature(df) - виводить кількість тривог в залежності від температури повітря для кожної області\n
 -Функція def process_temperature(df) - використовуючи попередню функцію, виводить кількість тривог при додатній та від'ємній температурі повітря. Як бачимо, більше тривог траплялося, коли було тепліше
