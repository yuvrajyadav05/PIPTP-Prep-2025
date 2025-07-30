Function funn(Integer a, Integer b)
    Integer c
    For (each c from 2 to 4)
        If ((a mod c) < (b mod c))
            a = a mod 3
        Else
            If (5 mod 3 > b)
                a = b
                b = 1
            End if
        End if
    End for
    return a + b
End function funn()


CORRECT OPTION IS 6
