# Основы автоматизированных информационных систем управления предприятием.
## Задание.
В рамках данного проекта для автоматизации выбраны следующие функции автоматизированной системы “МЧС”:
  1.	регистрация вызова;
  2.  учет кадров;
  3.  учет материальной части;
  4.  график дежурств;
  5.  отчет о вызове.
- _Функция 1 “Регистрация вызова”_  
Данная функция предназначена для приема и регистрации вызовов. Эта цель достигается за счет того, что при вызове в БД заносится информация о времени его приема, инициаторе и причине вызова, операторе принявшем заявку, отряде спасателей и адресе происшествия.  
В реализации данной функции участвуют следующие объекты предметной области: оператор, инициатор вызова, отряд спасателей.  
Автоматизация данной функции позволит быстро фиксировать вызовы от населения.
- _Функция 2 “Учет кадров”_  
Данная функция предназначена для поддержки процесса управления персоналом службы. Эта цель достигается за счет того, что в БД накапливается информация о сотрудниках, в том числе та, которая в неавтоматизированном режиме собирается работниками отдела кадров.  
Особенности автоматизированной реализации функции состоят в том, что в базе данных размещаются сведения о контактных телефонах сотрудника, позволяющие обеспечить руководству быструю связь с ним в чрезвычайных ситуациях.  
Ожидается, что автоматизация данной функции позволит повысить быстродействие и снизить трудоемкость получения сведений о сотрудниках за счет использования оперативных запросов к компьютерной базе данных и формирования аналитических отчетов на ее основе.
- _Функция 3 “Учет материальной части”_  
Данная функция предназначена для учета имущества службы. Эта цель достигается за счет того, что всё имущество отделения, подлежащее возврату, приписывается к работникам службы (спасательное снаряжение, транспортные средства, инвентарь).  
Особенности автоматизированной реализации функции состоят в том, что в базе данных размещаются инвентарные номера имущества и регистрационные номера транспортных средств.  
Ожидается, что автоматизация данной функции позволит повысить быстродействие и снизить трудоемкость получения сведений о материальной базе отделения за счет использования оперативных запросов к компьютерной базе данных и формирования аналитических отчетов на ее основе.
- _Функция 4 “График дежурств”_  
Данная функция предназначена для процесса создания графика дежурств. Эта цель достигается за счет того, что формируется суточный наряд который дежурит в указанные в графике дни. 
Особенности реализации функции состоят в том, что в суточный наряд входят определенные отряды спасателей. Состав этих групп может меняться, однако переход сотрудников из одной группы в другую запрещен. Система должна предусмотреть невозможность включения в график дежурств отряда, если общее количество дежурств в месяце превышает 12.
Автоматизация данной функции позволит быстро составлять график дежурств и направлять оператором на вызовы отряды входящие в состав дежурного наряда.
- _Функция 5 “Отчет о вызове”_  
Данная функция предназначена для процесса создания отчетов о вызовах. Эта цель достигается за счет того, что в базу вносится необходимая информация о происшествии, проведенных мероприятиях.  
Особенности реализации функции состоят в том, что соответствующему вызову генерируется номер отчета. Отчет составляется спасателями выезжающими на место происшествия.
Автоматизация данной функции позволит быстро составлять отчеты о происшествии.  

По всем функциям должны быть реализованы отчеты.

____

**FinalLabWithSwap.dt** - конфигурация с мобильным обменом.
