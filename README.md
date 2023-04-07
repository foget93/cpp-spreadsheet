# cpp-spreadsheet
Проект: Электронная таблица

Сборка CMAKE(MacOS or Unix):
1) cpp-spreadsheet % mkdir build
2) cpp-spreadsheet % cd build
3) build % cmake ../spreadsheet
4) build % cmake --build .

Проверка сборки (запуск тестов):
1) build % ./spreadsheet

Ожидание: 

TestPositionAndStringConversion OK
TestPositionToStringInvalid OK
TestStringToPositionInvalid OK
TestEmpty OK
TestInvalidPosition OK
TestSetCellPlainText OK
TestClearCell OK
TestFormulaArithmetic OK
TestFormulaReferences OK
TestFormulaExpressionFormatting OK
TestFormulaReferencedCells OK
TestErrorValue OK
TestErrorDiv0 OK
TestEmptyCellTreatedAsZero OK
TestFormulaInvalidPosition OK
TestPrint OK
TestCellReferences OK
TestFormulaIncorrect OK
TestCellCircularReferences OK
