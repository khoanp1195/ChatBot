

GraphQL:
GraphQL là một ngôn ngữ truy vấn cho API và là một runtime để thực hiện các truy vấn đó bằng dữ liệu hiện có. 
Khi sử dụng trong React Native, GraphQL cung cấp một cách mạnh mẽ và linh hoạt để tương tác với dữ liệu, giúp tối ưu hóa và đơn giản hóa việc lấy dữ liệu từ server. Dưới đây là mô tả chi tiết về cách sử dụng GraphQL trong ứng dụng React Native.  Mutation trong GraphQL
Mutation là một loại yêu cầu trong GraphQL được sử dụng để thay đổi dữ liệu trên server, chẳng hạn như tạo mới, cập nhật hoặc xóa dữ liệu. Trong GraphQL, mutation tương tự như các phương thức POST, PUT, DELETE trong REST API.
 Endpoint trong GraphQL là URL mà client sẽ gửi các truy vấn (query) và mutation tới. Khác với REST API có nhiều endpoint cho các hành động khác nhau, GraphQL chỉ có một endpoint duy nhất cho tất cả các truy vấn và mutation.
 Mutation: Sử dụng để thay đổi dữ liệu trên server (tạo, cập nhật, xóa).
Endpoint: URL duy nhất cho tất cả các truy vấn và mutation trong GraphQL.
refetch: Dùng để làm mới dữ liệu sau khi thực hiện mutation.
