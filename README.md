# SE-Lab-7


## میزان پوشش کد پیش از اضافه کردن تست ها
![1](https://github.com/mtndaghyani/SE-Lab-7/assets/59438691/77e1b264-8286-418d-9c94-dcc35ba8d529)


تست کلاس `PersonRepositoryTest`

1. **`testInsert`**:
   - تست درج شخص در ریپازیتوری با موفقیت.
   - استفاده از `assertEquals` یا `assertThat` برای بررسی بازگشت مقدار مورد انتظار.
   - بررسی اینکه آیا تابع `insert` درست فراخوانی شده است یا خیر.

2. **`testUpdate`**:
   - تست به‌روزرسانی اطلاعات شخص در ریپازیتوری.
   - بررسی فراخوانی صحیح تابع `update`.

3. **`testDelete`**:
   - تست حذف شخص از ریپازیتوری.
   - بررسی فراخوانی صحیح تابع `delete`.

4. **`testGet`**:
   - تست دریافت اطلاعات شخص از ریپازیتوری.
   - استفاده از `assertEquals` یا `assertThat` برای بررسی بازگشت مقدار مورد انتظار.
   - بررسی فراخوانی صحیح تابع `get`.


## پوشش کد پس از اضافه کردن تست های جدید
![2-2](https://github.com/mtndaghyani/SE-Lab-7/assets/59438691/93f0d113-e61a-4bcc-9dbe-2c10a0a74d4a)

تست کلاس `TrafficTest`

1. **`testSetCurrentTrafficLight`**:
   - تست تنظیم و بازیابی درست وضعیت چراغ راهنمایی فعلی.
   - اطمینان از صحت تابع `setCurrentTrafficLight` و `getCurrentTrafficLight`.

2. **`testSetIntenseCarTraffic`**:
   - تست تنظیم و بازیابی وضعیت ترافیک شدید.
   - اطمینان از صحت تابع `setIntenseCarTraffic` و `intenseCarTraffic`.

3. **`testSetMaxSpeedAllowed`**:
   - تست تنظیم و بازیابی سرعت حداکثر مجاز.
   - اطمینان از صحت تابع `setMaxSpeedAllowed` و `getMaxSpeedAllowed`.

4. **`testSetMinSpeedAllowed`**:
   - تست تنظیم و بازیابی سرعت حداقل مجاز.
   - اطمینان از صحت تابع `setMinSpeedAllowed` و `getMinSpeedAllowed`.

5. **`testSetStreetDirectionFlow`**:
   - تست تنظیم و بازیابی جریان جاده.
   - اطمینان از صحت تابع `setStreetDirectionFlow` و `getStreetDirectionFlow`.

6. **`testAllTrafficProperties`**:
   - تست یکجا تمامی ویژگی‌های ترافیک.
   - اطمینان از هماهنگی و درستی تمام توابع `set` و `get`.

 کلاس `PersonServiceTest`

1. **`testInsert_shouldInsertPersonWithSuccessWhenAllPersonsInfoIsFilled`**:
   - تست افزودن شخص جدید با موفقیت در صورت پر شدن اطلاعات شخص.
   - استفاده از Mockito برای شبیه‌سازی تابع `insert` در `PersonRepository`.
   - اطمینان از برابری شیء با شیء مورد انتظار.

2. **`testInsert_shouldThrowPersonExceptionWhenPersonIsNull`**:
   - تست بررسی پرتابع استثناء (`PersonException`) در صورت ارسال شخص `null`.
   - بررسی محتوای استثناء و مطابقت با پیام خطا.

3. **`testInsert_shouldThrowPersonExceptionWhenPersonNameIsNull`**:
   - تست بررسی پرتابع استثناء در صورت ارسال شخص با نام `null`.

4. **`testInsert_shouldThrowPersonExceptionWhenPersonNameIsBlank`**:
   - تست بررسی پرتابع استثناء در صورت ارسال شخص با نام خالی.

5. **`testInsert_shouldThrowPersonExceptionWhenPersonGenderIsNull`**:
   - تست بررسی پرتابع استثناء در صورت ارسال شخص با جنسیت `null`.

6. **`testUpdate_shouldUpdatePersonWithSuccessWhenAllPersonsInfoIsFilled`**:
   - تست به‌روزرسانی اطلاعات شخص با موفقیت.

7. **`testUpdate_shouldThrowPersonExceptionWhenPersonIsNull`**:
   - تست بررسی پرتابع استثناء در صورت ارسال شخص `null` برای به‌روزرسانی.

8. **`testGet_shouldReturnPersonWhenNameIsNotNull`**:
   - تست بازگرداندن شخص با نام مشخص.

9. **`testGet_shouldThrowPersonExceptionWhenNameIsNull`**:
   - تست بررسی پرتابع استثناء در صورت ارسال نام `null` برای دریافت شخص.

10. **`testDelete_shouldDeletePersonWithSuccessWhenNameIsNotNull`**:
    - تست حذف شخص با موفقیت با نام مشخص.



11. **`testDelete_shouldThrowPersonExceptionWhenNameIsNull`**:
    - تست بررسی پرتابع استثناء در صورت ارسال نام `null` برای حذف شخص.



## پوشش نهایی کد پس از اضافه کردن همه تست ها
![3](https://github.com/mtndaghyani/SE-Lab-7/assets/59438691/776584df-ac34-4896-8b81-6dc1dd0a3f78)
