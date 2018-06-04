Book {
	_id: "",
	isbn_number: "",
	author: [],
	keywords: [],
	copies: [],
	borrowed_copies: [],
	available: ""
}

Student {
	_id: "",
	name: "",
	books_borrowed: [],
	return_dates: [
		{
			book: "",
			return_date: ""
		}
	]
}

Author {
	_id: "",
	name: "",
	books: []
}

Librarian {
	username: "",
	password: ""
}