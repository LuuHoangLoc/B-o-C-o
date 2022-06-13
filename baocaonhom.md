# BÁO CÁO

# GIỚI THIỆU GIT

## GIT là gì?

 là phần mềm quản lý mã nguồn phân tán (Distributed Version Control System – DVCS), nó là một trong những hệ thống quản lý phiên bản phân tán phổ biến nhất hiện nay. Git cung cấp cho mỗi lập trình viên kho lưu trữ (repository) riêng chứa toàn bộ lịch sử thay đổi.

## GIT có tác dụng như thế nào?

1. Lưu lại lịch sử các version của bất kỳ thay đổi nào của dự án. Giúp xem lại các sự thay đổi hoặc khôi phục (revert) lại sau này.

2. Việc chia sẻ code trở nên dễ dàng hơn, lập trình viên có thể để public cho bất kỳ ai, hoặc private chỉ cho một số người có thẩm quyền có thể truy cập và lấy code về.

Vốn là một VCS nên Git cũng ghi nhớ lại toàn bộ lịch sử thay đổi của source code trong dự án. Lập trình sửa file, thêm dòng code tại đâu, xóa dòng code ở hàng nào…đều được Git ghi nhận và lưu trữ lại.

## GIT hoạt động như thế nào?

Sự khác biệt chính giữa Git và bất kỳ VCS nào khác (bao gồm Subversion…) là cách Git nghĩ về dữ liệu của nó.

Về mặt khái niệm, hầu hết các hệ thống khác đều lưu trữ thông tin dưới dạng danh sách các thay đổi dựa trên file. Các hệ thống này (CVS, Subversion, Perforce, Bazaar, v.v.) coi thông tin chúng lưu giữ dưới dạng một tập hợp các file và những thay đổi được thực hiện đối với mỗi file theo thời gian.

## Ưu điểm của GIT là:

- Dễ sử dụng, thao tác nhanh, gọn, lẹ và rất an toàn.

- Sẽ dàng kết hợp các phân nhánh (branch), có thể giúp quy trình làm việc code theo nhóm đơn giản hơn rất nhiều.

- Chỉ cần clone mã nguồn từ kho chứa hoặc clone một phiên bản thay đổi nào đó từ kho chứa, hoặc một nhánh nào đó từ kho chứa là bạn có thể làm việc ở mọi lúc mọi nơi.

- Deployment sản phẩm của bạn một cách không thể nào dễ dàng hơn.

## Hạn chế của GIT là:

- Thuật toán SHA1 sự va chạm giá trị băm làm cho các pc thông thường làm hư hỏng một kho git.

- Sử dụng GIT trên hệ điều hành Microsoft Windows hơi phức tạp.

- Các tập tin không liên quan mà luôn luôn bị thay đổi, Git có thể chịu thiệt thòi hơn các hệ thống khác bởi vì các tập tin không được giữ dấu viết từng cái riêng lẻ.

## Các thuật ngữ GIT quan trọng là:

- Branch - Commit - Checkout - Fetch - Fork - Head - Index - Master - Merge - Origin - Pull - Push - Rebase - Remote - Repository - Stash - Tags - Upstream

## Các lệnh GIT cơ bản là:
1. git config
2. git init
3. git clone
4. git status
5. git add
6. git commit
7. git push/ git pull
8. git branch
9. git checkout
10. git stash
11. git merge
12. git reset
13. git remote
## So sánh GIT và các phần mềm khác
Đây là điểm khác biệt quan trọng giữa Git và gần như tất cả các VCS khác. Nó khiến Git phải xem xét lại hầu hết mọi khía cạnh của kiểm soát phiên bản mà hầu hết các hệ thống khác đã sao chép từ thế hệ trước. Điều này làm cho Git giống như một hệ thống tệp nhỏ với một số công cụ cực kỳ mạnh mẽ được xây dựng trên nó, thay vì chỉ đơn giản là một VCS.
## Khi sử dụng GIT

- Lưu lại được các phiên bản khác nhau của mã nguồn dự án phần mềm.

- Khôi phục lại mã nguồn từ 1 phiên bản bất kỳ.

- Dễ dàng so sánh của các phiên bản.

- Phát hiện được ai đã sửa phần nào làm phát sinh lỗi.

- Khôi phục lại tập tin bị mất.

- Dễ dàng thử nghiệm, mở rộng tính năng của dự án mà không làm ảnh hưởng đến phiên bản chính (master branch).

- Giúp phối hợp thực hiện dự án trong một nhóm 1 cách hiệu quả.

## Khi không sử dụng GIT

- Không khôi phục được mã code lỡ xóa gây ra lỗi.

- Không quản lý được những người đã sửa code làm phát sinh lỗi

- Không khôi phục được tập tin đã bị mất.

- Khả năng phối hợp dự án trong nhóm bị hạn chế.
