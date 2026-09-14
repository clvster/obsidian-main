---
Заметка создана: "2026-09-14"
---
# Напряжённость поля точечного заряда
$$
\vec{E} = k \frac{q}{r^2} \frac{\vec{r}}{r}
$$
$\vec{r}$ -- вектор, соединяющий заряд и точку.
$r_{x} = x_{a} - x_{q}$
$r_{x} = y_{a} - y_{q}$
$r_{z} = z_{a} - z_{q}$


$$
\vec{dE} = k \frac{dq}{r^2} \frac{\vec{r}}{r}
$$
$$
\vec{E} = \int{\vec{dE}}
$$ -- принцип суперпозиции


# Плотность заряда
Линейная плотность заряда $\tau = \frac{Q}{L} \rightarrow$ $\tau = \frac{dq}{dl} \to dq = \tau dL$ 
Поверхностная плотность заряда $\frac{\sigma Q}{S} \to \sigma = \frac{dq}{dS} \to dq = \sigma dS$
Объёмная плотность заряда $\rho = \frac{dq}{dV} \to dq = \rho dV$


# 1. Напряжённость поля заряженного кольца в точке на перепендикуляре к центру
$$
dE = k \frac{dq}{r^2}
$$
$$
dE_x = dE sin \alpha
$$
$$
dE_y = dEcos \alpha
$$
$$
E = \int{dE_y} = \int_{0}^{Q_k}{k \frac{dq}{r^2} \frac{h}{r}} = k \frac{Q_k h}{r^3}
$$

Алгоритм:
1. Выделим dq;
2. Рисуем и записываем $\vec{dE}$;
3. Смотрим поведение $dE$ при к другой dq
4. Выбираем что интегрировать;
5. Интегрируем;


# 2. Напряжённость поля отрезка в точке на оси отрезка
$$
dE = k \frac{dq}{r^2}
$$
$$
E = \int{dE} = \int{k \frac{dq}{r^2}} = \int_{a}^{a + L}{k \frac{\tau dr}{r^2}} = k \tau (\frac{1}{a} - \frac{1}{a + L}) 
$$



# 3. Напряжённость поля полукольца в центре полукольца
$$
dE = k \frac{dq}{r^2}
$$
$$
dE_x = dEsin\alpha
$$
$$
dE_y = dEcos\alpha
$$
$$
E = \int{dE_y} = \int{k \frac{dq}{R^2} cos \alpha} = \frac{k}{R^2} \int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}{\tau Rd\alpha cos \alpha} = \frac{2k \tau}{R}
$$


# 4. Напряжённость поля бесконечно длинной нити
$dE = k \frac{dq}{r^2}$; $\int{dE_{x}} = 0;$ $dE_{y} = dE\cos \alpha$;
$E = \int{dE_{y}} = \int{k \frac{dq}{r^2} \cos \alpha}$
$dq = \tau dx$; $dx = \frac{dL}{\cos \alpha}$; $dL = r dx$
$dq = \tau \frac{rdx}{\cos \alpha}$

$$
E = \int{k \tau \frac{rdx}{r^2 cos \alpha} \cos{\alpha}} = k\tau \int{\frac{d \alpha}{r}};
$$
$$
E = kr \int{\frac{\cos {\alpha} d\alpha}{h}} = \frac{k\tau}{h} \int_{-\frac{\pi}{2}}^{\frac{\pi}{2}} {\cos{\alpha}d\alpha}
$$
$$
E = \frac{2k\tau}{h}
$$
$$
E = \frac{2k \tau}{h} = |k = \frac{1}{4\pi \varepsilon_0}| = \frac{\tau}{2\pi \varepsilon_0h}
$$
$$
E = \frac{k\tau}{h} \int{\cos{\alpha} d\alpha} -база\ для\ родственников
$$


# 5. Напряжённость поля отрезка на перпендикуляре к середине
$$
E = \frac{k \tau}{h} \int{\cos{\alpha d\alpha}} = \frac{2k\tau}{h}\int_{0}^{\beta}{\cos{\alpha} d\alpha} = \frac{2k \tau}{h} \sin{\beta}
$$
$\sin{\beta} = \frac{\frac{L}{2}}{\sqrt{h^2 + \frac{L^2}{h}}}$


# 6. Напряжённость поля луча
$$
|E| = \sqrt{E^2_{x} + E^2_y}
$$
$E_x = \int{dE \sin{\alpha}}$; $E_{y} = \int_{0}^{\frac{\pi}{2}}{dE\cos {\alpha}}$; 
$E_{x} = \frac{k\tau}{h}$; $E_{y} = \frac{k\tau}{h}$


# 7. Напряжённость поля диска на перпендикуляре к середине
$E = \int{dE_{y}}$; $dE_{y} = dE - \cos{\alpha}$;
$dE = k \frac{dL}{x^2} = k \frac{\sigma dL dr}{x^2}$
$E = \int{k\sigma \int{\int{\frac{dL dr}{x^2}}}}\cos{\alpha} = k\sigma \int{\frac{dr}{x^2}} \cos{\alpha} = \int_{0}^{2\pi r} {dL}$
$\int_{0}^{2\pi r}{dL} = 2\pi r$; $\cos{\alpha} = \frac{h}{x}$

$$
E = k \sigma \int{\frac{2\pi r}{x^2} \frac{h}{x}dr} = |x = (r^2 + h^2)^{\frac{1}{2}}| = 2\pi hk \sigma \int{\frac{rdr}{(r^2 + h^2)^{\frac{3}{2}}}}
$$

$$
E = 2\pi hk \sigma \int_0^{R}{-\frac{1}{2} \frac{d(r^2 + h^2)}{(r^2 + h^2)^{\frac{3}{2}}}}=...
$$

На лабы не забыть разбиться