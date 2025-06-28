SELECT Product, SUM(Amount) AS TotalSales
FROM Sales
GROUP BY Product;
SELECT Product, SUM(Amount) AS TotalSales
FROM Sales
GROUP BY Product
HAVING SUM(Amount) > 200;
