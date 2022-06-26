# proof
Accelerated Federated Learning with Dynamic Model Partition for H-IoT Online Proof
Energy consumption can be reduced if we minimize the right side of (16) while ensuring the stability of the queue in (11). Given the observed $Q(\tau )$, we can get
\begin{equation}
\begin{array}{l}
	\Delta Q(\tau ) + V \cdot (C({\delta _\tau },\tau )|Q(\tau ))\\
	\le K + (VC({\delta _\tau },\tau )\\
	\begin{array}{*{20}{c}}
		{}&{}
	\end{array} + Q(\tau )(E({\delta _\tau },\tau ) - \sigma B/T)|Q(\tau ))\\
	= K + V \cdot (C({\delta _\tau }^*,\tau ))\\
	\begin{array}{*{20}{c}}
		{}&{}
	\end{array} + ((E({\delta _\tau }^*,\tau ) - \sigma B/T)|Q(\tau ))\\
	\le K + V \cdot {c^ * }
\end{array}
\end{equation} 
where ${{\delta }_{\tau }}^{*}$ is the optimal partition point for time slot $\tau $. According to the conditions (18) and (19) satisfied by the optimal w-only strategy [12], it can be seen that (17) holds.
\begin{equation}
	C({{\delta }_{\tau }}^{*},\tau )={{c}^{*}}
\end{equation}
\begin{equation}
	E({{\delta }_{\tau }}^{*},\tau )-\sigma B/T\le 0
\end{equation}
By accumulating the conclusion of (17) for the time slots, we can get
\begin{equation}
	\begin{array}{l}
		(K + V \cdot {c^ * })\tau  \ge \mathop {lim}\limits_{\tau  \to T} \mathop \sum \limits_{t = 0}^\tau  \{ \Delta Q(\tau ) + V \cdot C({\delta _\tau },\tau )|Q(\tau )\} \\
		= \left[ {L(Q(T))} \right] + V \cdot \mathop {lim}\limits_{\tau  \to T} \mathop \sum \limits_{t = 0}^\tau  \left[ {C({\delta _\tau },\tau )|Q(\tau )} \right]\\
		\ge V \cdot \mathop {lim}\limits_{\tau  \to T} \mathop \sum \limits_{t = 0}^\tau  \left[ {C({\delta _\tau },\tau )|Q(\tau )} \right]
	\end{array}
\end{equation} 
Therefore, we can obtain (15) by deforming (20).
