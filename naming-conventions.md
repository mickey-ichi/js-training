Naming Convention List 
======================

1.  Naming convention for boolean value
2.  Naming convention for action related to
    string value
3.  Naming convention for data manipulation
    (Add)
4.  Naming convention for data manipulation
    (Update)
5.  Naming convention for data manipulation
    (Delete)
6.  Naming convention for data manipulation
    (Write)
7.  Naming convention for data manipulation
    (Read)
8.  Naming convention for data manipulation
    (Verification/Check/Validation)
9.  Naming convention for permission / prohibition
10. Hungarian Notation
11. Naming Method
12. Notes for naming
​
    
1.Naming convention for boolean value
-----------------------------
​
Naming convention for boolean value
​
| Place | Word | Meaning| Example|
|---|---|---|---|
| Tiền tố	 | is | Đang ở trong trạng thái gì không ?	 | isEnabled |
| Tiền tố	 | can | Có thể xử lí được không?	 | canRemove |
| Tiền tố	 | should | Có nên thực hiện lệnh không?| shouldMigrate |
| Tiền tố	 | need | Có cần thực hiện gì không?| needFileCopy |
| Tiền tố	 | has | Có cái data/ properties mong muốn không| hasConnection |
| Tiền tố	 | exists | Có tồn tại data hoặc properties mong muốn không?| exists(dir) |
| Tiền tố	 | contains | Có chứa data hay properties không?| contains(item) |


2.Naming convention for action related to string value 
--------------------------------------------------------
​
Naming convention for action related to
string value
​
| Place | Word | Meaning| Example|
|---|---|---|---|
| Tiền tố	 | find | Tìm thông tin(tiền đề cho việc có thể tìm thấy)| findString |
| Tiền tố	 | search | Tìm thông tin(tiền đề cho việc không thể tìm thấy)| searchString |
| Tiền tố	 | seek | Tìm thông tin liên tục theo thứ tự| file.seek() |
| Tiền tố	 | extract | Extract thông tin theo điều kiện| hash.extract() |
| Tiền tố	 | filter | Loại trừ thông tin theo các điều kiện nhất định| filter() |
| Tiền tố	 | replace | Thay thế dữ liệu hiện có| String.replace() |
| Tiền tố	 | join | Kết hợp dữ liệu hiện có| String.join() |
| Tiền tố	 | parse | Phân tích dữ liệu hiện có| String.Parse() |


3.Naming convention for data manipulation (add) 
---------------------------------------------
​
Naming convention for data manipulation (add)
​
| Place | Word | Meaning| Example|
|---|---|---|---|
| Tiền tố	 | set | Set data | setProperty |
| Tiền tố	 | add | Thêm data hoặc object| addList |
| Tiền tố	 | put | Thêm data hoặc object| hash.put(key,value) |
| Tiền tố	 | insert | Chèn data hoặc object| insertQueue |
| Tiền tố	 | append | Thêm data hoặc object vào cuối| appendQueue |
| Tiền tố	 | push | Thêm data hoặc object vào vị trí đầu| pushQueue |
| Tiền tố	 | prepend | Thêm data hoặc object vào vị trí đầu| prependQueue |
| Tiền tố	 | register | Đăng kí data hoặc object| registerStorage |
| Tiền tố	 | create | Tạo data hoặc file mới| createAccount |
| Tiền tố	 | new | Tạo data hoặc file mới| newAccount |
| Tiền tố	 | make | Xử lí data cũ để tạo data hoặc file mới| makeFile |
| Tiền tố	 | build | Tập hợp dữ liệu và tệp từ dữ liệu hiện có| buildFile |
| Tiền tố	 | from | Sử dụng data hiện có để tạo file hoặc data| fromConfigFile |
| Tiền tố	 | generate | Tạo file hoặc data theo 1 rule nào đó| generateFile |


4.Naming convention for data manipulation (update)
---------------------------------------
​
Naming convention for data manipulation(update)
​
| Place | Word | Meaning| Example|
|---|---|---|---|
| Tiền tố	 | update | Update data cũ| updateAccount |
| Tiền tố	 | upgrade | Thay đổi data thành cái tốt hơn| upgradeAccount |
| Tiền tố	 | apply | Áp dụng data có sẵn| applyAccount|
| Tiền tố	 | refresh | Cập nhật lại data cũ| refreshAccount |
| Tiền tố	 | changed | Thay đổi data hiện có| changedAccount |
| Tiền tố	 | modified | Sửa data có sẵn| modifiedAccount |
| Tiền tố	 | revised | Sửa data có sẵn| revisedAccount |
| Tiền tố	 | enable | Enable khả năng sử dụng của data có sẵn| enableAccount |
| Tiền tố	 | disable | Disable khả năng sử dụng của data có sẵn| disableAccount |
| Tiền tố	 | fix | Giải quyết vấn đề của data| fixAccount |
| Tiền tố	 | repair | Sửa data| repairAccount |
| Tiền tố	 | restore | Restore data| restoreAccount |
| Tiền tố	 | recover | Recover data| recoverAccount |
| Tiền tố	 | edit | Edit data| editAccount |
| Tiền tố	 | adjust | Điều chỉnh data| adjustString |
| Tiền tố	 | adapt | Điều chỉnh dữ liệu hiện có| adaptString |
| Tiền tố	 | convert | Chuyển đổi dữ liệu hiện có| convertString |
| Tiền tố	 | to | Chuyển đổi dữ liệu hiện có sang cái gì| toString |


5.Naming convention for data manipulation(delete) 
-----------------------------------------------
​
Naming convention for data manipulation(delete)
​
| Place | Word | Meaning| Example|
|---|---|---|---|
| Tiền tố	 | delete | Xoá data hiện có( không revert được)|deleteAccount
| Tiền tố	 | remove | Xoá data hiện có(revert được)| removeAccount |
| Tiền tố	 | trash | Xoá data hiện có(có revert được)| trashAccount|
| Tiền tố	 | erase | Xóa dữ liệu hiện có (có thể ghi lại)| eraseAccount |
| Tiền tố	 | clear | Clear data hiện có về trạng thái khởi tạo| clearAccount |
| Tiền tố	 | flush | Xoá data về trạng thái ban đầu| flushAccount |
| Tiền tố	 | reset | Reset data về trạng thái ban đầu| resetAccount |
| Tiền tố	 | dispose | Giải phóng dữ liệu hiện có(có thể tái sử dụng)| disposeAccount |
| Tiền tố	 | destroy | Loại bỏ dữ liệu hiện có (không thể sử dụng lại)| destroyAccount |
| Tiền tố	 | unregister | Hủy dữ liệu đã đăng ký| unregisterStorage |
| Tiền tố	 | unset | Bỏ định nghĩa data đã được định nghĩa| unsetAccount |
| Tiền tố	 | pop | Trích xuất và loại bỏ dữ liệu đầu tiên| popQueue |
| Tiền tố	 | initialize | Khởi tạo dữ liệu hiện có| initialize() |
| Tiền tố	 | edit | Edit data| editAccount |
| Tiền tố	 | adjust | Điều chỉnh data| adjustString |
| Tiền tố	 | adapt | Điều chỉnh dữ liệu hiện có| adaptString |
| Tiền tố	 | convert | Chuyển đổi dữ liệu hiện có| convertString |
| Tiền tố	 | to | Chuyển đổi dữ liệu hiện có sang cái gì| toString |


6.Naming convention for data manipulation(write)
---------------------------------------
​
Naming convention for data manipulation(write)
​
| Place | Word | Meaning| Example|
|---|---|---|---|
| Tiền tố	 | save | Lưu data hiện có|saveAccount
| Tiền tố	 | output | Xuất dữ liệu hiện có| outputAccount |
| Tiền tố	 | export | Xuất dữ liệu hiện có| exportAccount|
| Tiền tố	 | write | Write dữ liệu hiện có| writeAccount |
| Tiền tố	 | store | Store dữ liệu hiện có| storeAccount |
| Tiền tố	 | send | Gửi data hiện có| sendAccount |
| Tiền tố	 | commit | Xác định data| commitAccount |


7.Naming Convention for data manipulation (Read) 
---------------------------------------------
​
​
Naming Convention for data manipulation (Read)
​
| Place | Word | Meaning| Example|
|---|---|---|---|
| Tiền tố	 | get | Get data hiện có|getAccount
| Tiền tố	 | load |Load data hiện có| loadAccount |
| Tiền tố	 | input | Nhập data hiện có| inputAccount|
| Tiền tố	 | import | Import data hiện có| importAccount |
| Tiền tố	 | read | Read data| readAccount |
| Tiền tố	 | restore | Restore data hiện có| restoreAccount |
| Tiền tố	 | fetch | Get data hiện có| fetchAccount |


8.Naming convention for data manipulation(verification) 
-----------------------------------------------------
​
​
Naming convention for data manipulation(verification)
​
| Place | Word | Meaning| Example|
|---|---|---|---|
| Tiền tố	 | check | Check data có phù hợp với điều kiện không|checkAccount
| Tiền tố	 | test |Check xem data có thoả mãn điều kiện không| testAccount |
| Tiền tố	 | validate | Validate data có đúng không| validateAccount|
| Tiền tố	 | compare |So sánh data| compareAccount |
| Tiền tố	 | verify | Verify data| verifyAccount |


9.Naming convention for permission / prohibition  
----------------------------------
​
Naming convention for permission / prohibition
​
| Place | Word | Meaning| Example|
|---|---|---|---|
| Tiền tố	 | allow | Cấp quyền sử dụng|allowAccount
| Tiền tố	 | disallow |Bỏ cấp quyền sử dụng| disallowAccount |
| Tiền tố	 | accept | Chấp nhận| acceptAccount|
| Tiền tố	 | deny |Deny| denyAccount |
| Tiền tố	 | refuse | Từ chối yêu cầu| refuseAccount |
| Tiền tố	 | reject | Từ chối  yêu cầu| rejectAccount |
| Tiền tố	 | grant | Cung cấp một loạt các quyền| grantAccount |
| Tiền tố	 | revoke | Tước quyền| revokeAccount |


10.Hungarian Notation 
------------------
​
Ký hiệu Hungary là một quy ước đặt tên định danh trong lập trình máy
tính, trong đó tên của một biến hoặc hàm cho biết ý định hoặc loại của
nó và trong một số phương ngữ là type của nó.
​
List system hungarian notation
​
| Place | Word | Meaning| Example|
|---|---|---|---|
| Tiền tố	 | b or f | Loại logic (binary)|bDirtyFlag
| Tiền tố	 | ch |Loại ký tự (character)| chSeparator |
| Tiền tố	 | by | loại byte| byGrayLevel|
| Tiền tố	 | i or n |Loại số nguyên (integer)| nPower |
| Tiền tố	 | l | Số nguyên dài (long)| lDate |
| Tiền tố	 | ui | Số nguyên không dấu (unsigned integer)| uiCount |
| Tiền tố	 | w | Loại word (word)| wLanguageCode |
| Tiền tố	 | dw | Loại từ kép (dword)| dwSize |
| Tiền tố	 | f or fp | Single-precision floating-point (float)| fPrice |
| Tiền tố	 | d or dp | Double precision floating point type (double)| dPi |
| Tiền tố	 | p or lp | Loại pointer (pointer)| pDirectSound |
| Tiền tố	 | s | Loại string (string)| sPlayerName |
| Tiền tố	 | sz | Zero-terminated string type (string zero)| szFileName |
| Tiền tố	 | fn | Function pointer type (function pointer)| fnCallback |
| Tiền tố	 | h | loại handle (handle)| hThread |
| Tiền tố	 | g_ | biến global| g_iErrorCode |
| Tiền tố	 | c_ | constant (const)| c_nBufferSize |
| Tiền tố	 | s_ | Biến (static)| s_pLookupTable|
| Tiền tố	 | m_ | Member variables| m_nLength|


11.Naming method 
-------------
​

Camelcase (Lower camel case)
:   chữ cái đầu tiên của từ ghép là chữ thường\
     ví dụ) `getInputReader`

Pascal case (Upper camel case)
:   chữ cái đầu tiên của từ ghép là chữ Hoa\
     ví dụ) `GetInputReader`

Snake case
:   Nối từ bằng dấu \_\
     ví dụ) `quoted_printable_encode`

Chain case
:   Nối từ bằng dấu gạch thường\
     ví dụ) `Get-Process`


12.Notes for naming 
--------------------
​
Dùng từ rõ ràng
:   Khi dùng những từ trừu tượng, hãy bao gồm thông tin rõ ràng như "ở
    đâu" và "cái gì" trong cách đặt tên.

Tránh những tên chung chung
:   -   Khi đặt tên, hãy cân nhắc xem chúng có mục đích gì
    -   Các biến để lưu trữ tạm thời thì là ngoại lệ
​

Tránh những tên dài
:   Thiết kế tên sao cho dài nhất có khoảng 20 ký tự. Tên dài khó đọc
    hơn, gõ rườm rà và gây ra lỗi chính tả. Ngoài ra, nếu từ viết tắt
    phổ biến như một quy ước, hãy làm theo ví dụ sau:(Ex：`average` thì
    viết thành `avg`

Đặt tên sao cho  dễ hiểu
:   Nếu tên viết tắt và nhầm lẫn với các yếu tố khác, hãy sử dụng tên có
    thể hiểu được mà không cần viết tắt nhiều hơn mức cần thiết.

Sử dụng một tên cụ thể
:   Bao gồm cụ thể những thông tin mà biến hoặc hàm đó đảm nhiệm .

Xác định từ trái nghĩa
:   Xác định đúng các từ trái nghĩa để có sự thống nhất trong quy ước
    đặt tên.
    -   `Start` ⇔ `Stop`
    -   `Top` ⇔ `Bottom`
    -   `High` ⇔ `Low`
    -   `Big` ⇔ `Small`
    -   `Attach` ⇔ `Detach`
    -   `Input` ⇔ `Output`
    -   `Show` ⇔ `Hide`
​

Thêm thông tin bằng cách sử dụng hậu tố / tiền tố
:   Đặt một đơn vị vào biến lưu trữ giá trị.(`px` hoặc `ms` )
​
