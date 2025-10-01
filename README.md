# Quest-o-4-fun-o
def verificar_par_impar(numero):
    """
    Verifica se um número é par ou ímpar.
    
    Args:
        numero (int): Número inteiro a ser verificado
    
    Returns:
        str: "Par" se o número for par, "Ímpar" se for ímpar
    """
    if numero % 2 == 0:
        return "Par"
    else:
        return "Ímpar"


def eh_par(numero):
    """
    Verifica se um número é par.
    
    Args:
        numero (int): Número inteiro a ser verificado
    
    Returns:
        bool: True se par, False se ímpar
    """
