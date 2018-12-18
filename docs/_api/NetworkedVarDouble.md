---
title: NetworkedVarDouble
permalink: /api/networked-var-double/
---

<div style="line-height: 1;">
	<h2 markdown="1">NetworkedVarDouble ``class``</h2>
	<p style="font-size: 20px;"><b>Namespace:</b> MLAPI</p>
	<p style="font-size: 20px;"><b>Assembly:</b> MLAPI.dll</p>
</div>
<p>A NetworkedVar that holds doubles and support serialization</p>

<div>
	<h3 markdown="1">Inherited Properties</h3>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``bool`` isDirty { get; set; }</b></h4>
		<h5 markdown="1">Inherited from: ``NetworkedVar<double>``</h5>
	</div>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``float`` LastSyncedTime { get; set; }</b></h4>
		<h5 markdown="1">Inherited from: ``NetworkedVar<double>``</h5>
	</div>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``double`` Value { get; set; }</b></h4>
		<h5 markdown="1">Inherited from: ``NetworkedVar<double>``</h5>
	</div>
</div>
<br>
<div>
	<h3 markdown="1">Inherited Fields</h3>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public [``NetworkedVarSettings``](/MLAPI/api/networked-var-settings/) Settings;</b></h4>
		<h5 markdown="1">Inherited from: ``NetworkedVar<double>``</h5>
	</div>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``OnValueChangedDelegate<double>`` OnValueChanged;</b></h4>
		<h5 markdown="1">Inherited from: ``NetworkedVar<double>``</h5>
	</div>
</div>
<br>
<div>
	<h3>Public Constructors</h3>
	<div style="line-height: 1; ">
		<h4 markdown="1"><b>public [``NetworkedVarDouble``](/MLAPI/api/networked-var-double/)();</b></h4>
	</div>
	<div style="line-height: 1; ">
		<h4 markdown="1"><b>public [``NetworkedVarDouble``](/MLAPI/api/networked-var-double/)([``NetworkedVarSettings``](/MLAPI/api/networked-var-settings/) settings);</b></h4>
	</div>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">[``NetworkedVarSettings``](/MLAPI/api/networked-var-settings/) settings</p>
		</div>
	<div style="line-height: 1; ">
		<h4 markdown="1"><b>public [``NetworkedVarDouble``](/MLAPI/api/networked-var-double/)(``double`` value);</b></h4>
	</div>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``double`` value</p>
		</div>
	<div style="line-height: 1; ">
		<h4 markdown="1"><b>public [``NetworkedVarDouble``](/MLAPI/api/networked-var-double/)([``NetworkedVarSettings``](/MLAPI/api/networked-var-settings/) settings, ``double`` value);</b></h4>
	</div>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">[``NetworkedVarSettings``](/MLAPI/api/networked-var-settings/) settings</p>
		</div>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``double`` value</p>
		</div>
</div>
<br>
<div>
	<h3 markdown="1">Inherited Methods</h3>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``void`` ResetDirty();</b></h4>
		<h5 markdown="1">Inherited from: ``NetworkedVar<double>``</h5>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``bool`` IsDirty();</b></h4>
		<h5 markdown="1">Inherited from: ``NetworkedVar<double>``</h5>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``bool`` CanClientRead(``uint`` clientId);</b></h4>
		<h5 markdown="1">Inherited from: ``NetworkedVar<double>``</h5>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``uint`` clientId</p>
		</div>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``void`` WriteDelta(``Stream`` stream);</b></h4>
		<h5 markdown="1">Inherited from: ``NetworkedVar<double>``</h5>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``Stream`` stream</p>
		</div>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``bool`` CanClientWrite(``uint`` clientId);</b></h4>
		<h5 markdown="1">Inherited from: ``NetworkedVar<double>``</h5>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``uint`` clientId</p>
		</div>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``void`` ReadDelta(``Stream`` stream, ``bool`` keepDirtyDelta);</b></h4>
		<h5 markdown="1">Inherited from: ``NetworkedVar<double>``</h5>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``Stream`` stream</p>
		</div>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``bool`` keepDirtyDelta</p>
		</div>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``void`` SetNetworkedBehaviour([``NetworkedBehaviour``](/MLAPI/api/networked-behaviour/) behaviour);</b></h4>
		<h5 markdown="1">Inherited from: ``NetworkedVar<double>``</h5>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">[``NetworkedBehaviour``](/MLAPI/api/networked-behaviour/) behaviour</p>
		</div>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``void`` ReadField(``Stream`` stream);</b></h4>
		<h5 markdown="1">Inherited from: ``NetworkedVar<double>``</h5>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``Stream`` stream</p>
		</div>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``void`` WriteField(``Stream`` stream);</b></h4>
		<h5 markdown="1">Inherited from: ``NetworkedVar<double>``</h5>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``Stream`` stream</p>
		</div>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``string`` GetChannel();</b></h4>
		<h5 markdown="1">Inherited from: ``NetworkedVar<double>``</h5>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``string`` ToString();</b></h4>
		<h5 markdown="1">Inherited from: ``object``</h5>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``bool`` Equals(``object`` obj);</b></h4>
		<h5 markdown="1">Inherited from: ``object``</h5>
		<h5><b>Parameters</b></h5>
		<div>
			<p style="font-size: 20px; color: #444;" markdown="1">``object`` obj</p>
		</div>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``int`` GetHashCode();</b></h4>
		<h5 markdown="1">Inherited from: ``object``</h5>
	</div>
	<br>
	<div style="line-height: 1;">
		<h4 markdown="1"><b>public ``Type`` GetType();</b></h4>
		<h5 markdown="1">Inherited from: ``object``</h5>
	</div>
</div>
<br>