1.  Tổng quan về Angular

-   Angular là một framework phát triển ứng dụng web được phát triển và
    duy trì bởi Google. Đây là một trong những framework phổ biến nhất
    hiện nay để xây dựng các ứng dụng web một trang (Single Page
    Application - SPA).

-   Những điểm nổi bật của Angular:

    -   Typescript: Angular được viết bằng TypeScript - một ngôn ngữ mở
        rộng của JavaScript, cung cấp tính năng kiểu dữ liệu tĩnh và lập
        trình hướng đối tượng

    -   Component-Based: Ứng dụng Angular được xây dựng từ các component
        độc lập, có thể tái sử dụng. Mỗi component bao gồm:

        -   Template (HTML)

        -   Styles (Css/Scss/Sass)

        -   Class (TypeScript/JavaScript)

        -   Metadata (Decorators)

    -   Có bộ công cụ phát triển mạnh mẽ:

        -   Angular CLI để tạo và quản lý project

        -   Built-in dependency injection

        -   Routing mạnh mẽ

        -   Forms module với validation

        -   HTTP client

        -   Testing utilities

-   Angular có các cơ chế change detection hiệu quả và compiler AOT để
    tối ưu hiệu suất ứng dụng

-   Angular được hỗ trợ bởi Google và nhiều lập trình viên trên toàn thế
    giới; Angular có hệ sinh thái phong phú với nhiều thư viện, công cụ
    và tài liệu hướng dẫn.

2.  Các thành phần cốt lõi của Angular

-   Component

    -   Components là đơn vị xây dựng cơ bản trong ứng dụng Angular,
        hoạt động như các khối code độc lập. Mỗi component là sự kết hợp
        giữa template HTML và code TypeScript/JavaScript đi kèm, tạo nên
        một thành phần UI có tính đóng gói cao và tái sử dụng được.

    -   Components có thể:

        -   Hoạt động độc lập và dễ dàng tích hợp vào hoặc gỡ bỏ khỏi
            ứng dụng

        -   Đại diện cho các phần tử UI từ đơn giản đến phức tạp:

            -   Một nút bấm đơn lẻ với logic xử lý đi kèm

            -   Một form phức tạp với nhiều trường nhập liệu

            -   Một trang hoàn chỉnh chứa nhiều components con

            -   Một module chức năng gồm nhiều trang liên quan

    -   Đặc biệt, components có khả năng lồng ghép (nesting), cho phép
        một component cha có thể chứa và điều khiển nhiều components
        con, tạo nên cấu trúc UI có tính phân cấp rõ ràng và dễ quản lý.
        Điều này giúp xây dựng giao diện người dùng một cách module hóa
        và linh hoạt.

-   Service

    -   Là các class chứa logic nghiệp vụ và dữ liệu có thể chia sẻ giữa
        các components

    -   Giúp tách biệt logic xử lý khỏi components, làm cho code dễ bảo
        trì và tái sử dụng

    -   Thường xử lý:

        -   Gọi API

        -   Xử lý business logic

        -   Quản lý state

        -   Chia sẻ dữ liệu

-   Dependency Injection

    -   Là cơ chế tự động cung cấp instance của một class khi cần

    -   Giúp quản lý các dependencies giữa các components và services

    -   Cho phép thay đổi implementation mà không ảnh hưởng đến code sử
        dụng

-   Routing

    -   Là cơ chế điều hướng giữa component/page trong ứng dụng

    -   Routing trong angular hỗ trợ

        -   Quản lý navigation state

        -   Bảo vệ routes với guards

        -   Tối ưu performance với lazy loading

        -   Quản lý URL parameters

-   Binding

    -   Angular hỗ trợ binding 1 chiều, 2 chiều

-   Directive

    -   Là các markers trên DOM elements cho biết Angular cần thực hiện
        một số hành vi cụ thể. Có 3 loại directives chính:

        -   Component Directives:

            -   Chính là các component

        -   Structural Directives

            -   Giúp thay đổi layout DOM: \*ngFor, \*ngSwitch,
                \*ngSwitchCase,\*ngIf, \*ngSwitchDefault

        -   Attribute Directives

            -   Thay đổi appearance hoặc behavior của element:
                \*ngClass, \*ngStyle
