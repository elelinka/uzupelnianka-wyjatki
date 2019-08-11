## Wyjątki

1. Wyjątki dzielimy na kontrolowane, które trzeba obsłużyć i niekontrolowane, które można, ale nie trzeba obsłużyć.
1. Wyjątki niekontrolowane dziedziczą po klasie RuntimeException.
1. Wyjątki rzucamy korzystając z instrukcji throw, jeśli rzucamy wyjątek kontrolowany musimy dodatkowo w sygnaturze metody/konstruktora zadeklarować wyjątek używając słowa throws.
1. Do bloku try-catch możemy dodać dodatkowo blok finally, który wykona się zawsze, niezależnie, czy w bloku try wyjątek wystąpił, czy nie.