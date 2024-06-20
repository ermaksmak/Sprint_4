# qa_python

1. **test_add_new_book_add_books**
   - Проверяет, что новая книга добавляется в коллекцию с пустым жанром по умолчанию.

2. **test_add_new_book_invalid_length_more_40**
   - Проверяет, что книга с названием длиной более 40 символов не добавляется в коллекцию.
  
3. **test_add_new_book_invalid_length_is_0**
   - Проверяет, что книга с названием длиной 0 символов не добавляется в коллекцию.

4. **test_get_list_of_favorites_books_have_books**
   - Проверяет, что книги добавленные в избранное, правильно присутствуют в списке избранных книг.

5. **test_set_book_genre**
   - Проверяет установку жанра для книги и правильное получение этого жанра.

6. **test_set_book_genre_invalid**
   - Проверяет, что установка неподдерживаемого жанра для книги не изменяет её жанр.

7. **test_get_books_with_specific_genre**
   - Проверяет, что метод возвращает книги с указанным жанром.

8. **test_get_books_for_children**
   - Проверяет, что метод правильно возвращает книги, подходящие для детей, и исключает те, которые не подходят.

9. **test_add_book_in_favorites**
   - Проверяет, что книга может быть добавлена в избранные.

10. **test_delete_book_from_favorites**
   - Проверяет удаление книги из списка избранных.

11. **test_add_favorites_nonexistent_book**
    - Проверяет, что попытка добавить несуществующую книгу в избранное не приводит к ошибке и книга не добавляется.

12. **test_add_duplicate_book_in_favorites**
    - Проверяет, что при добавлении одной и той же книги в избранное несколько раз, она добавляется только один раз.

13. **test_set_and_get_genre**
    - Проверяет установку и получение жанра для книги.

14. **test_adding_book_genre**
    - Проверяет, что новая книга по умолчанию добавляется с пустым жанром.

15. **test_books_with_no_genre**
    - Проверяет, что метод возвращает правильно книги без жанра.

16. **test_invalid_genre**
    - Проверяет, что книги с несуществующим жанром не находятся.

17. **test_get_books_genre**
    - Проверяет правильное получение словаря всех книг с их жанрами.

18. **test_get_books_for_children_no_books**
    - Проверяет, что метод возвращает пустой список, если нет книг, подходящих для детей.