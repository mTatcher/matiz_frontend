<template>
    <b-container>
        <b-row>
            <h2>Техобслуживание:</h2>
        </b-row>
        <b-row>
            <b-col sm="2" class="tenk">
            </b-col>
            <b-col sm="10" align-v="center">
                <p class="lead">
                    Для Дэу Матиз проводить техобслуживание необходимо раз в 10 тыс.км.<br />
                    Лучше потратить незначительную сумму запланировано, чем экстренно тратить суммы и нервы, возможно вдалеке от дома, терять время на поиск запчастей и ремонт.
                </p>
            </b-col>
        </b-row>
        <b-row>
            <b-col sm="10" align-v="center">
                <p class="lead">
                    Замена масла и фильтров на каждом ТО обязательна.<br />
                    От качественного моторного масла и своевременной замены фильтров зависит насколько долго прослужит двигатель Вашего Дэу Матиз.
                </p>
            </b-col>
            <b-col sm="2" class="oil">
            </b-col>
        </b-row>
        <b-row>
            <b-col sm="2" class="brake">
            </b-col>
            <b-col sm="10" align-v="center">
                <p class="lead">
                    Проверка шин, тормозных колодок и элементов ходовой части и их необходимая замена сбережет Ваш автомобиль от катастрофических поломок в дороге.
                </p>
            </b-col>
        </b-row>
        <b-row>
            <p class="lead">
                Одна из самых распространенных ошибок - это подмена технического обслуживания простой заменой масла. Не надо забывать, что в регламент ТО входит обязательная диагностика всех систем автомобиля, включая тормоза, двигатель, ходовую часть и так далее. Чего не делается при простой замене масла!!!!<br />
                Пригоняйте свой "Матиз" к нам на ТО и будьте спокойны и уверены на дороге!
            </p>
        </b-row>
        <b-row align-h="center">
            <b-img src="../img/graphic.jpg" />
        </b-row>
    </b-container>
</template>

<script>
    export default {
        name: 'Teh',
    };
</script>

<style scoped>
    .tenk{
        background: url(../img/10k.jpg);
        background-size:contain;
        background-position-x:center;
        background-repeat: no-repeat;
    }
    .oil{
        background: url(../img/oil.png);
        background-size:contain;
        background-position-x:center;
        background-repeat: no-repeat;
    }
    .brake{
        background: url(../img/brake.png);
        background-size:contain;
        background-position-x:center;
        background-repeat: no-repeat;
    }
</style>