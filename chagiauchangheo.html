import React, { useState, useEffect } from 'react';
import { Book, Moon, Sun, Search, ArrowLeft, Menu, X, Bookmark, Share2, MoreVertical, ChevronLeft, ChevronRight, Type } from 'lucide-react';

// Dữ liệu sách - Đã sắp xếp đúng thứ tự 1-13
const bookData = [
  {
    id: 1,
    vol: "Tập 1",
    title: "Để không có tiền vẫn tạo ra tiền",
    subtitle: "Rich Dad Poor Dad",
    color: "from-yellow-400 to-orange-500",
    summary: "Cuốn sách khởi đầu, so sánh tư duy giữa người cha nghèo (học vấn cao nhưng chật vật tài chính) và người cha giàu (tư duy đầu tư, kinh doanh).",
    content: "Chương 1: Cha Giàu Cha Nghèo\n\nTác giả kể về hai người cha của mình. Một người là cha ruột, có học thức cao nhưng luôn gặp khó khăn về tài chính. Người kia là cha của bạn thân, tuy chưa học hết lớp 8 nhưng lại trở thành một trong những người giàu nhất Hawaii..."
  },
  {
    id: 2,
    vol: "Tập 2",
    title: "Sử dụng đồng vốn",
    subtitle: "Cashflow Quadrant",
    color: "from-blue-400 to-indigo-500",
    summary: "Giải thích về Kim tứ đồ (Cashflow Quadrant) và cách chuyển từ người làm công/làm tư sang chủ doanh nghiệp/nhà đầu tư.",
    content: "Chương 1: Tại sao không kiếm lấy một công việc?\n\nĐối với một người coi trọng công việc làm công ăn lương, thật khó để giải thích tại sao mình không muốn tìm việc làm. Kim tứ đồ chia con người làm 4 nhóm..."
  },
  {
    id: 3,
    vol: "Tập 3",
    title: "Hướng dẫn đầu tư",
    subtitle: "Guide to Investing",
    color: "from-green-400 to-emerald-600",
    summary: "Hướng dẫn chi tiết về các cấp bậc đầu tư và cách để trở thành một nhà đầu tư lão luyện.",
    content: "Nội dung đang được cập nhật từ file PDF..."
  },
  {
    id: 4,
    vol: "Tập 4",
    title: "Con giàu con thông minh",
    subtitle: "Rich Kid Smart Kid",
    color: "from-pink-400 to-rose-500",
    summary: "Giúp các bậc cha mẹ khai phá tiềm năng tài chính cho con cái ngay từ khi còn nhỏ.",
    content: "Nội dung đang được cập nhật từ file PDF..."
  },
  {
    id: 5,
    vol: "Tập 5",
    title: "Để có sức mạnh về tài chính",
    subtitle: "Retire Young Retire Rich",
    color: "from-purple-400 to-violet-600",
    summary: "Nghỉ hưu sớm và nghỉ hưu giàu. Cách sử dụng đòn bẩy tài chính để đạt tự do nhanh chóng.",
    content: "Nội dung đang được cập nhật từ file PDF..."
  },
  {
    id: 6,
    vol: "Tập 6",
    title: "Những câu chuyện thành công",
    subtitle: "Prophecy",
    color: "from-red-400 to-red-600",
    summary: "Tuyển tập những câu chuyện thực tế từ những người đã áp dụng kiến thức của Rich Dad để thành công.",
    content: "Nội dung đang được cập nhật từ file PDF..."
  },
  {
    id: 7,
    vol: "Tập 7",
    title: "Ai đã lấy tiền của tôi?",
    subtitle: "Who Took My Money?",
    color: "from-teal-400 to-teal-600",
    summary: "Cách đầu tư để kiếm lợi nhuận cao nhất và nhanh nhất, đồng thời bảo vệ tài sản.",
    content: "Nội dung đang được cập nhật từ file PDF..."
  },
  {
    id: 8,
    vol: "Tập 8",
    title: "Để có tích sự đến tiền của tôi",
    subtitle: "Making Money Work",
    color: "from-cyan-400 to-blue-500",
    summary: "Hiểu rõ về dòng tiền và cách bắt tiền bạc làm việc cật lực cho mình.",
    content: "Nội dung đang được cập nhật từ file PDF..."
  },
  {
    id: 9,
    vol: "Tập 9",
    title: "Những bí mật về tiền bạc",
    subtitle: "Financial Secrets",
    color: "from-amber-400 to-yellow-600",
    summary: "Những điều mà bạn không bao giờ được học ở nhà trường về tiền bạc.",
    content: "Nội dung đang được cập nhật từ file PDF..."
  },
  {
    id: 10,
    vol: "Tập 10",
    title: "Trước khi bạn thôi việc",
    subtitle: "Before You Quit Your Job",
    color: "from-lime-400 to-green-600",
    summary: "10 bài học thực tế dành cho những ai muốn khởi nghiệp xây dựng công ty riêng.",
    content: "Nội dung đang được cập nhật từ file PDF..."
  },
  {
    id: 11,
    vol: "Tập 11",
    title: "Trường dạy kinh doanh",
    subtitle: "Business School",
    color: "from-indigo-400 to-purple-500",
    summary: "Giá trị của kinh doanh theo mạng và những kỹ năng kinh doanh cốt lõi.",
    content: "Nội dung đang được cập nhật từ file PDF..."
  },
  {
    id: 12,
    vol: "Tập 12",
    title: "Xây dựng con thuyền tài chính",
    subtitle: "Building Your Ark",
    color: "from-sky-400 to-blue-600",
    summary: "Làm thế nào để bảo vệ tương lai tài chính của bạn và gia đình trước những biến động.",
    content: "Nội dung đang được cập nhật từ file PDF..."
  },
  {
    id: 13,
    vol: "Tập 13",
    title: "Nâng cao chỉ số IQ tài chính",
    subtitle: "Increase Your Financial IQ",
    color: "from-fuchsia-400 to-pink-600",
    summary: "Làm thế nào để thông minh hơn với tiền bạc của bạn qua 5 chỉ số IQ tài chính.",
    content: "Nội dung đang được cập nhật từ file PDF..."
  },
];

const App = () => {
  const [selectedBook, setSelectedBook] = useState(null);
  const [isDarkMode, setIsDarkMode] = useState(false);
  const [searchQuery, setSearchQuery] = useState("");
  const [isSidebarOpen, setIsSidebarOpen] = useState(false);
  const [fontSize, setFontSize] = useState(18);

  // Filter books based on search
  const filteredBooks = bookData.filter(book => 
    book.title.toLowerCase().includes(searchQuery.toLowerCase()) || 
    book.vol.toLowerCase().includes(searchQuery.toLowerCase())
  );

  const toggleTheme = () => setIsDarkMode(!isDarkMode);

  // Component: Book Card for Library View
  const BookCard = ({ book, onClick }) => (
    <div 
      onClick={() => onClick(book)}
      className={`group relative cursor-pointer rounded-xl overflow-hidden shadow-lg transition-all duration-300 hover:shadow-2xl transform hover:-translate-y-1 ${isDarkMode ? 'bg-gray-800' : 'bg-white'}`}
    >
      <div className={`h-32 w-full bg-gradient-to-r ${book.color} flex items-center justify-center`}>
        <span className="text-4xl font-bold text-white opacity-30 select-none">{book.id}</span>
      </div>
      <div className="p-5">
        <div className="flex justify-between items-center mb-2">
          <span className={`text-xs font-bold px-2 py-1 rounded-full ${isDarkMode ? 'bg-gray-700 text-blue-300' : 'bg-blue-100 text-blue-800'}`}>
            {book.vol}
          </span>
        </div>
        <h3 className={`font-bold text-lg mb-1 leading-tight ${isDarkMode ? 'text-white' : 'text-gray-900'}`}>
          {book.title}
        </h3>
        <p className={`text-sm mb-3 ${isDarkMode ? 'text-gray-400' : 'text-gray-500'}`}>
          {book.subtitle}
        </p>
        <p className={`text-sm line-clamp-2 ${isDarkMode ? 'text-gray-300' : 'text-gray-600'}`}>
          {book.summary}
        </p>
      </div>
      {/* Hover Effect Overlay */}
      <div className="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-10 transition-all duration-300 flex items-center justify-center opacity-0 group-hover:opacity-100">
        <span className="bg-white text-black px-4 py-2 rounded-full font-bold shadow-lg transform scale-90 group-hover:scale-100 transition-transform">
          Đọc ngay
        </span>
      </div>
    </div>
  );

  // Component: Reader Interface
  const ReaderView = ({ book, onBack }) => (
    <div className={`flex flex-col h-screen ${isDarkMode ? 'bg-gray-900 text-gray-200' : 'bg-gray-50 text-gray-800'}`}>
      {/* Reader Toolbar */}
      <div className={`h-16 border-b flex items-center justify-between px-4 shadow-sm z-10 ${isDarkMode ? 'bg-gray-800 border-gray-700' : 'bg-white border-gray-200'}`}>
        <button onClick={onBack} className="flex items-center space-x-2 hover:opacity-70">
          <ArrowLeft size={20} />
          <span className="hidden sm:inline font-medium">Thư viện</span>
        </button>
        
        <div className="flex-1 text-center px-4">
          <h2 className="text-sm sm:text-base font-bold truncate max-w-xs sm:max-w-md mx-auto">{book.vol}: {book.title}</h2>
        </div>

        <div className="flex items-center space-x-3">
          <button onClick={() => setFontSize(Math.max(14, fontSize - 2))} className="p-2 rounded hover:bg-gray-200 dark:hover:bg-gray-700">
            <span className="text-xs">A-</span>
          </button>
          <button onClick={() => setFontSize(Math.min(32, fontSize + 2))} className="p-2 rounded hover:bg-gray-200 dark:hover:bg-gray-700">
            <span className="text-lg">A+</span>
          </button>
          <button className="p-2 rounded hover:bg-gray-200 dark:hover:bg-gray-700 hidden sm:block">
            <Bookmark size={20} />
          </button>
        </div>
      </div>

      {/* Reader Content */}
      <div className="flex-1 overflow-y-auto">
        <div className="max-w-3xl mx-auto p-6 sm:p-10 min-h-screen shadow-sm" style={{ backgroundColor: isDarkMode ? '#1f2937' : '#ffffff' }}>
          
          <div className={`w-full h-48 rounded-xl mb-8 bg-gradient-to-r ${book.color} flex flex-col justify-center items-center text-white p-6 text-center`}>
             <h1 className="text-3xl font-bold mb-2">{book.title}</h1>
             <p className="opacity-90">{book.subtitle}</p>
          </div>

          <div className="prose max-w-none" style={{ fontSize: `${fontSize}px`, lineHeight: '1.8' }}>
            <p className="whitespace-pre-line text-justify">
              {book.content}
            </p>
            
            <div className="my-10 p-6 border rounded-lg bg-gray-50 dark:bg-gray-800 dark:border-gray-700">
              <h3 className="font-bold mb-2">Thông báo hệ thống</h3>
              <p className="text-sm opacity-80">
                Đây là bản demo giao diện. Để đọc toàn bộ nội dung từ file RAR bạn đã tải lên, 
                hệ thống thực tế sẽ cần giải nén file và nạp nội dung PDF vào khung hiển thị này.
                <br/><br/>
                Hiện tại, bạn có thể trải nghiệm sự mượt mà của giao diện chuyển trang và quản lý tủ sách.
              </p>
            </div>

            {/* Simulated text specifically for demo */}
            <p>
              "Có hai người cha dạy bảo tôi. Một người giàu và một người nghèo. Một người có học vấn cao và trí tuệ sắc sảo; ông có bằng tiến sĩ... Người kia chưa học hết lớp 8..."
            </p>
            <p className="mt-4">
              Cả hai người đàn ông đều thành công trong sự nghiệp của họ, làm việc chăm chỉ suốt đời. Cả hai đều kiếm được nhiều tiền. Nhưng một người luôn phải vật lộn về tài chính suốt đời, còn người kia thì trở thành một trong những người giàu nhất Hawaii.
            </p>
             <p className="mt-4">
              Một người chết để lại hàng chục triệu đô la cho gia đình, từ thiện và nhà thờ. Người kia để lại những hóa đơn chưa thanh toán.
            </p>
          </div>

          {/* Navigation Footer */}
          <div className="flex justify-between mt-16 pt-8 border-t border-gray-200 dark:border-gray-700">
            <button 
              disabled={book.id === 1}
              onClick={() => setSelectedBook(bookData.find(b => b.id === book.id - 1))}
              className={`flex items-center space-x-2 px-4 py-2 rounded-lg transition ${book.id === 1 ? 'opacity-50 cursor-not-allowed' : 'hover:bg-gray-100 dark:hover:bg-gray-700'}`}
            >
              <ChevronLeft size={20} />
              <span>Tập trước</span>
            </button>
            
            <button 
              disabled={book.id === 13}
              onClick={() => setSelectedBook(bookData.find(b => b.id === book.id + 1))}
              className={`flex items-center space-x-2 px-4 py-2 rounded-lg transition ${book.id === 13 ? 'opacity-50 cursor-not-allowed' : 'hover:bg-gray-100 dark:hover:bg-gray-700'}`}
            >
              <span>Tập tiếp</span>
              <ChevronRight size={20} />
            </button>
          </div>

        </div>
      </div>
    </div>
  );

  return (
    <div className={`min-h-screen transition-colors duration-300 ${isDarkMode ? 'bg-gray-900 text-white' : 'bg-gray-100 text-gray-900'} font-sans`}>
      {selectedBook ? (
        <ReaderView book={selectedBook} onBack={() => setSelectedBook(null)} />
      ) : (
        <>
          {/* Header */}
          <header className={`sticky top-0 z-20 backdrop-blur-md border-b ${isDarkMode ? 'bg-gray-900/90 border-gray-700' : 'bg-white/90 border-gray-200'}`}>
            <div className="container mx-auto px-4 h-16 flex items-center justify-between">
              <div className="flex items-center space-x-2">
                <Book className="text-yellow-500" size={28} />
                <h1 className="text-xl font-bold tracking-tight hidden sm:block">Rich Dad <span className="text-yellow-500">Reader</span></h1>
              </div>

              {/* Search Bar */}
              <div className="flex-1 max-w-md mx-4">
                <div className="relative group">
                  <Search className="absolute left-3 top-1/2 transform -translate-y-1/2 text-gray-400 group-focus-within:text-yellow-500 transition-colors" size={18} />
                  <input
                    type="text"
                    placeholder="Tìm kiếm sách..."
                    value={searchQuery}
                    onChange={(e) => setSearchQuery(e.target.value)}
                    className={`w-full pl-10 pr-4 py-2 rounded-full border outline-none transition-all ${isDarkMode ? 'bg-gray-800 border-gray-700 focus:border-yellow-500 text-white' : 'bg-gray-50 border-gray-200 focus:border-yellow-500 focus:bg-white'}`}
                  />
                </div>
              </div>

              <div className="flex items-center space-x-2">
                <button onClick={toggleTheme} className={`p-2 rounded-full transition-colors ${isDarkMode ? 'hover:bg-gray-800 text-yellow-400' : 'hover:bg-gray-200 text-gray-600'}`}>
                  {isDarkMode ? <Sun size={20} /> : <Moon size={20} />}
                </button>
              </div>
            </div>
          </header>

          {/* Main Library Content */}
          <main className="container mx-auto px-4 py-8">
            <div className="mb-8">
              <h2 className="text-2xl font-bold mb-2">Thư viện Dạy Con Làm Giàu</h2>
              <p className={`text-sm ${isDarkMode ? 'text-gray-400' : 'text-gray-600'}`}>
                Trọn bộ 13 tập kinh điển của Robert Kiyosaki
              </p>
            </div>

            {filteredBooks.length > 0 ? (
              <div className="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
                {filteredBooks.map((book) => (
                  <BookCard key={book.id} book={book} onClick={setSelectedBook} />
                ))}
              </div>
            ) : (
              <div className="text-center py-20 opacity-50">
                <p>Không tìm thấy cuốn sách nào phù hợp.</p>
              </div>
            )}
          </main>
        </>
      )}
    </div>
  );
};

export default App;
