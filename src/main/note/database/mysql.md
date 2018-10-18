
##### sql
    mysql整体架构？
        MySQL是由SQL接口，解析器，优化器，缓存，存储引擎等组成的。
    mysql内存结构？
    mysql索引？
    mysql count(1)、count(*)、count(column)区别？
        count(*)是对行的数目进行统计，包括NULL值，count(column)对特定列进行统计，不包括NULL值。
        
    mysql查询优化？
        任何情况下select count(*) from table是最优选择；
        尽量减少select count(*) from table where col1="value"这种查询；
        杜绝select count(col1) from table where col2="value"这种查询；
            
