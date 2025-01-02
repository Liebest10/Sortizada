
-- Função para determinar se o evento raro ocorre com 30% de chance
function eventoRaro1()
    local chance = math.random()
    -- Aumentando a probabilidade de 0.1% para 30%
    if chance <= 0.3 then
        return true
    else
        return false
    end
end

-- Função para determinar se o evento raro ocorre com 50% de chance
function eventoRaro2()
    local chance = math.random()
    -- Aumentando a probabilidade de 0.25% para 50%
    if chance <= 0.5 then
        return true
    else
        return false
    end
end

-- Chamando as funções e verificando os resultados
if eventoRaro1() then
    print("Você obteve o item raro na primeira tentativa!")
else
    print("Tente novamente na primeira tentativa!")
end

if eventoRaro2() then
    print("Você obteve o item raro na segunda tentativa!")
else
    print("Tente novamente na segunda tentativa!")
end
