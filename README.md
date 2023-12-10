# Weather-attacks
 -Функція def read_file(path) - зчитує файл csv та перетворює його на табличку, прибирає колонку city, оскільки для аналізу вона не потрібна<br />
 -Функція def calculate_max_attacks(df) - виводить місяць, у якому в конкретній області було найбільше тривог (тобто повідомлень з '💥', '📍', '⚠️')<br />
 -Функція def month_attack(df) - виводить кількості атак по місяцям, враховуючи всі, а не тільки табличні<br />
 -Функція def process_weather_data(df) - виводить кількість повідомлень для конкретної області в залежності від погоди<br />
 -Функція def region_temperature(df) - виводить кількість тривог в залежності від температури повітря для кожної області<br />
 -Функція def process_temperature(df) - використовуючи попередню функцію, виводить кількість тривог при додатній та від'ємній температурі повітря<br />
 -Функція def process_data(df) - знаходить кількість атак та тривог в залежності від пори доби<br />
 -Функція def flag_direction(df, show_statistics=True) - підраховує кількість конкретних положень прапора України біли Академії сухомутних військ. При зміні на False повертає список положень прапора у Львові в залежності від часу
