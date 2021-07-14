**ЗАДАЧА**

**В задаче следует разобраться в том, как определённые факторы влияют на факт погашения кредита в срок.**
----------------------------------------
2. **ОПИСАНИЕ ДАННЫХ:** 
- children — количество детей в семье
- days_employed — общий трудовой стаж в днях
- dob_years — возраст клиента в годах
- education — уровень образования клиента
- education_id — идентификатор уровня образования
- family_status — семейное положение
- family_status_id — идентификатор семейного положения
- gender — пол клиента
- income_type — тип занятости
- debt — имел ли задолженность по возврату кредитов
- total_income — ежемесячный доход
- purpose — цель получения кредита
----------------------------------------
3. **ОСНОВНЫЕ ПУНКТЫ И ЦЕЛИ ИССЛЕДОВАНИЯ:**
- Предобрботка данных:
  - определение и заполнение пропущенных значений;
  - замена типа данных;
  - удаление дубликатов;
  - выделение леммы в значениях столбца с целями получения кредита;
  - категоризация данных.
- Есть ли зависимость между определёнными факторами и возвратом кредита в срок?
4. **ИСПОЛЬЗУЮЕМЫЕ БИБЛИОТЕКИ:**
- Pandas
- IPython.display
