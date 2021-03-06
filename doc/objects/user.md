
## User


<table>
    <thead>
        <tr><th>Параметр</th><th>Тип</th><th>Значение</th></tr>
    </thead>
    <tbody>
        <tr>
            <td><code>id</code></td>
            <td><code>Integer</code></td>
            <td><p><br />Идентификатор пользователя</p></td>
        </tr><tr>
            <td><code>username</code></td>
            <td><code>String</code></td>
            <td><p><em>255 символов</em> <br />Имя пользователя. Может не совпадать с email</p></td>
        </tr><tr>
            <td><code>firstname</code></td>
            <td><code>String</code></td>
            <td><p><em>255 символов</em> <br />Имя</p></td>
        </tr><tr>
            <td><code>lastname</code></td>
            <td><code>String</code></td>
            <td><p><em>255 символов</em> <br />Фамилия</p></td>
        </tr><tr>
            <td><code>email</code></td>
            <td><code>String</code></td>
            <td><p><em>255 символов</em> <br />Email</p></td>
        </tr><tr>
            <td><code>types</code></td>
            <td>List of <code>Strings</code></td>
            <td><p><em>255 символов</em> <br />Массив ролей пользователя</p></td>
        </tr><tr>
            <td><code>status</code></td>
            <td><code>String</code></td>
            <td><p><em>255 символов</em> <em>active, deleted, blocked</em><br />Статус</p></td>
        </tr><tr>
            <td><code>additional_info</code></td>
            <td><a href="additionaluserinfo.md"><code>AdditionalUserInfo</code></a></td>
            <td><p><br />Объект <a href="#object_additionaluserinfo">AdditionalUserInfo</a></p></td>
        </tr><tr>
            <td><code>mailings</code></td>
            <td>List of <code>Strings</code></td>
            <td><p><em>255 символов</em> <em>news, finance, event, moderation, other</em><br />Список рассылок, на которые подписан пользователь</p></td>
        </tr><tr>
            <td><code>permissions</code></td>
            <td><code></code></td>
            <td><p><br />Список прав пользователя</p></td>
        </tr><tr>
            <td><code>account</code></td>
            <td>partial <a href="useraccount.md"><code>UserAccount</code></a><br />
(<code>id</code>, <code>balance</code>, <code>flags</code>, <code>type</code>)
</td>
            <td><p><br />Информация о финансовом аккаунте пользователя</p></td>
        </tr><tr>
            <td><code>agency</code></td>
            <td>partial <a href="agency.md"><code>Agency</code></a><br />
(<code>is_buyer</code>, <code>buyer_commission</code>, <code>overriding_commission</code>)
</td>
            <td><p><br />Информация о агентском аккаунте пользователя</p></td>
        </tr><tr>
            <td><code>agency_username</code></td>
            <td><code>String</code></td>
            <td><p><em>255 символов</em> <br />Username родительского агентства, если таковое есть</p></td>
        </tr><tr>
            <td><code>branch_username</code></td>
            <td><code>String</code></td>
            <td><p><em>255 символов</em> <br />Username родительского представительства, если таковое есть</p></td>
        </tr><tr>
            <td><code>bf</code></td>
            <td><code>Integer</code></td>
            <td></td>
        </tr><tr>
            <td><code>flags</code></td>
            <td>List of <code>Strings</code></td>
            <td><p><em>255 символов</em> </p></td>
        </tr><tr>
            <td><code>max_active_banners_count</code></td>
            <td><code>Integer</code></td>
            <td></td>
        </tr><tr>
            <td><code>active_banners_count</code></td>
            <td><code>Integer</code></td>
            <td></td>
        </tr><tr>
            <td><code>append_utm</code></td>
            <td><code>Boolean</code></td>
            <td><p><br />Deprecated</p></td>
        </tr><tr>
            <td><code>show_compact_view</code></td>
            <td><code>Boolean</code></td>
            <td><p><br />Компактное представление страницы "Объявления"</p></td>
        </tr><tr>
            <td><code>info_currency</code></td>
            <td><code>String</code></td>
            <td><p><em>3 символа</em> <br />Справочная валюта пользователя</p></td>
        </tr><tr>
            <td><code>currency</code></td>
            <td><code>String</code></td>
            <td><p><em>3 символа</em> <br />Валюта пользователя</p></td>
        </tr>
    </tbody>
</table>