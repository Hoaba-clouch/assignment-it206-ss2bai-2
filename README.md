# [Vận dụng cơ bản] PHÂN ĐỊNH LẠI 3 VAI TRÒ TRONG ĐỘI RIKKEIGO

## Phần 1 - Phân tích

Dưới đây là bảng phân tích 4 quy ước làm việc hiện tại của đội RikkeiGo, dựa trên trách nhiệm của từng vai trò trong Scrum:

| Quy ước | Đúng/Sai | Quyết định này thuộc về vai trò nào & vì sao | Triệu chứng nào ở Bối cảnh do quy ước này gây ra (nếu có) |
| :------- | :-------- | :--------------------------------------------- | :------------------------------------------------------ |
| **QU1.** Đức duyệt từng đoạn code và tự chọn thư viện bản đồ cho tính năng đặt xe. | **Sai** | Quyết định này thuộc về **Developers**. Developers là những người tự tổ chức, đa năng và tự quyết định cách triển khai kỹ thuật, bao gồm việc code review và lựa chọn công nghệ/thư viện. Việc Product Owner can thiệp sâu vào khía cạnh kỹ thuật làm giảm quyền tự chủ của Developers và không tối ưu vai trò của PO. | Triệu chứng: "Đức bị quá tải vì nhiều việc phải chờ anh xử lý" (do đảm nhận công việc kỹ thuật) và "lập trình viên phàn nàn bị bắt làm theo cách kém hiệu quả" (do không được tự quyết định cách làm kỹ thuật). |
| **QU2.** Để đội làm nhanh hơn, trong buổi Daily Scrum mỗi sáng, Lan giao cụ thể ai làm thẻ việc nào trong ngày. | **Sai** | Quyết định này thuộc về **Developers**. Developers tự tổ chức và chủ động phân chia công việc trong Sprint Backlog để đạt được Sprint Goal. Scrum Master (Lan) là người phục vụ, huấn luyện và loại bỏ rào cản, không có quyền ra lệnh hay giao việc cụ thể cho từng cá nhân. | Triệu chứng: "lập trình viên phàn nàn bị bắt làm theo cách kém hiệu quả" (do không được tự chủ phân công công việc). |
| **QU3.** Đức sắp xếp thứ tự ưu tiên Product Backlog dựa trên giá trị mang lại cho người đặt xe. | **Đúng** | Quyết định này thuộc về **Product Owner**. Product Owner (Đức) sở hữu Product Backlog và chịu trách nhiệm tối đa hóa giá trị sản phẩm. Việc sắp xếp thứ tự ưu tiên dựa trên giá trị mang lại cho người dùng là trách nhiệm cốt lõi của Product Owner. | Không có. |
| **QU4.** Developers tự đổi thứ tự hạng mục trong Product Backlog khi thấy một tính năng khác dễ làm hơn. | **Sai** | Quyết định này thuộc về **Product Owner**. Product Backlog thuộc sở hữu của Product Owner, người duy nhất có quyền quyết định thứ tự ưu tiên. Developers có thể cung cấp thông tin và ước lượng về độ phức tạp kỹ thuật, nhưng không được tự ý thay đổi thứ tự ưu tiên dựa trên tiêu chí "dễ làm". | Triệu chứng: "Đức bị quá tải vì nhiều việc phải chờ anh xử lý" (do thứ tự ưu tiên mà anh ấy đã đặt ra bị thay đổi ngoài ý muốn, làm ảnh hưởng đến kế hoạch giá trị sản phẩm). |

## Phần 2 - Vá lỗi

Dưới đây là các quy ước sai đã được viết lại để đúng vai và giải quyết các triệu chứng:

*   **QU1 (Sửa):** Developers tự tổ chức code review, thảo luận và chủ động lựa chọn thư viện bản đồ phù hợp cho tính năng đặt xe để tối ưu hóa hiệu quả kỹ thuật và chất lượng sản phẩm.
    *   *Giải quyết triệu chứng:* Giúp Developers chủ động, nâng cao hiệu quả làm việc và giảm tải cho Đức.

*   **QU2 (Sửa):** Trong buổi Daily Scrum, Developers tự đồng bộ tiến độ và chủ động phân công công việc cụ thể trong Sprint Backlog để đạt được Sprint Goal mà không cần Scrum Master giao việc.
    *   *Giải quyết triệu chứng:* Trao quyền tự chủ cho Developers trong việc phân công công việc, giải quyết phàn nàn về cách làm việc kém hiệu quả.

*   **QU4 (Sửa):** Developers cung cấp ước lượng và ý kiến về độ phức tạp kỹ thuật để hỗ trợ Product Owner trong việc sắp xếp thứ tự Product Backlog, nhưng quyền quyết định cuối cùng về ưu tiên các hạng mục thuộc về Product Owner.
    *   *Giải quyết triệu chứng:* Đảm bảo Product Owner duy trì quyền kiểm soát đối với Product Backlog, giảm gánh nặng quản lý và ra quyết định không cần thiết của Developers, giúp Đức tập trung vào tối đa hóa giá trị sản phẩm.