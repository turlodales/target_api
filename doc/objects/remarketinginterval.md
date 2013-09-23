
## RemarketingInterval

Временной интервал для ремаркетинга.

<table>
    <thead>
        <tr><th>Параметр</th><th>Тип</th><th>Значение</th></tr>
    </thead>
    <tbody>
        <tr>
            <td>`left`</td>
            <td>`Integer`</td>
            <td>*Обязательный*
<p>Минимальное значение параметра для показа объявления (левая граница временного интервала, дней назад)</p></td>
        </tr><tr>
            <td>`right`</td>
            <td>`Integer`</td>
            <td>*Обязательный*
<p>Максимальное значение параметра для показа объявления (правая граница интервала временного интервала, дней назад)</p></td>
        </tr><tr>
            <td>`type`</td>
            <td>`String`</td>
            <td>*Обязательный*
*255 символов*
*positive, negative*
<p>Условие показа объявления (попадание значения параметра в интервал, заданный <code>left</code> и <code>right</code>).</p></td>
        </tr>
    </tbody>
</table>