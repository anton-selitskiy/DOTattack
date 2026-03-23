# Voice Conversion with Optimal Transport

# New model with speaker embedding (any-to-any)

## Conversion from a training speaker to a training one

<table>
  <tr>
    <th>Source Speaker</th>
    <th>Target Speaker</th>
    <th>Conversion</th>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_kn/125-121124-0029.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_kn/839-130898-0065.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_kn/125-121124-0029__to__839__ref__839-130898-0065.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_kn/201-127786-0052.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_kn/887-123291-0008.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_kn/201-127786-0052__to__887__ref__887-123291-0008.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_kn/250-142276-0050.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_kn/1040-133433-0011.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_kn/250-142276-0050__to__1040__ref__1040-133433-0011.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_kn/298-126790-0042.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_kn/87-121553-0084.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_kn/298-126790-0042__to__87__ref__87-121553-0084.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_kn/446-123501-0025.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_kn/60-121082-0049.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_kn/446-123501-0025__to__60__ref__60-121082-0049.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>              
</table>

## Conversion from an unseen speaker to a speaker from training set

<table>
  <tr>
    <th>Source Speaker</th>
    <th>Target Speaker</th>
    <th>Conversion</th>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_unk_kn/6818-76332-0019.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk_kn/1034-121119-0074.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk_kn/6818-76332-0019__to__1034__ref__1034-121119-0074.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_unk_kn/1553-140048-0003.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk_kn/1040-133433-0048.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk_kn/1553-140048-0003__to__1040__ref__1040-133433-0048.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_unk_kn/5163-39921-0009.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk_kn/83-3054-0000.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk_kn/5163-39921-0009__to__83__ref__83-3054-0000.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
</table>

## Conversion from an training speaker to an unseen speaker

<table>
  <tr>
    <th>Source Speaker</th>
    <th>Target Speaker</th>
    <th>Conversion</th>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_kn_unk/839-130898-0084.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_kn_unk/7067-76048-0000.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_kn_unk/839-130898-0084__to__7067__ref__7067-76048-0000.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_kn_unk/1034-121119-0090.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_kn_unk/3240-131231-0071.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_kn_unk/1034-121119-0090__to__3240__ref__3240-131231-0071.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_kn_unk/1069-133699-0031.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_kn_unk/2416-152139-0027.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_kn_unk/1069-133699-0031__to__2416__ref__2416-152139-0027.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
</table>

## Conversion from unseen speaker to unseen

<table>
  <tr>
    <th>Source Speaker</th>
    <th>Target Speaker</th>
    <th>Conversion</th>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_unk/3235-28433-0044.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/2764-36619-0032.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/3235-28433-0044__to__2764__ref__2764-36619-0032.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_unk/3982-178459-0051.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/4397-15666-0006.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/3982-178459-0051__to__4397__ref__4397-15666-0006.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_unk/4362-15663-0085.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/6209-34599-0008.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/4362-15663-0085__to__6209__ref__6209-34599-0008.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_unk/4362-15663-0089.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/7367-86737-0076.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/4362-15663-0089__to__7367__ref__7367-86737-0076.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_unk/5049-25947-0013.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/6531-61334-0091.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/5049-25947-0013__to__6531__ref__6531-61334-0091.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_unk/8419-293469-0008.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/2893-139310-0040.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/8419-293469-0008__to__2893__ref__2893-139310-0040.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_unk/8975-270782-0024.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/8238-283452-0022.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/8975-270782-0024__to__8238__ref__8238-283452-0022.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_unk/1088-134315-0020.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/1447-130551-0031.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/1088-134315-0020__to__1447__ref__1447-130551-0031.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_unk/1246-124548-0000.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/2691-156745-0039.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/1246-124548-0000__to__2691__ref__2691-156745-0039.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="outputs_unk/1992-141719-0011.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/7148-7763-0008.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="outputs_unk/1992-141719-0011__to__7148__ref__7148-7763-0008.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>                
</table>


# Previous model with speaker ID
user_id=26
<audio controls>
        <source src="Results/converted_26_(0).wav" type="audio/wav">
        Your browser does not support the audio element.
</audio>

user_id=27
<audio controls>
        <source src="Results/converted_27_(1).wav" type="audio/wav">
        Your browser does not support the audio element.
</audio>

user_id=32
<audio controls>
        <source src="Results/converted_32_(2).wav" type="audio/wav">
        Your browser does not support the audio element.
</audio>

user_id=39
<audio controls>
        <source src="Results/converted_39_(3).wav" type="audio/wav">
        Your browser does not support the audio element.
</audio>

user_id=40
<audio controls>
        <source src="Results/converted_40_(4).wav" type="audio/wav">
        Your browser does not support the audio element.
</audio>

user_id=60
<audio controls>
        <source src="Results/converted_60_(5).wav" type="audio/wav">
        Your browser does not support the audio element.
</audio>

user_id=78
<audio controls>
        <source src="Results/converted_78_(6).wav" type="audio/wav">
        Your browser does not support the audio element.
</audio>

user_id=83
<audio controls>
        <source src="Results/converted_83_(7).wav" type="audio/wav">
        Your browser does not support the audio element.
</audio>

user_id=87
<audio controls>
        <source src="Results/converted_87_(8).wav" type="audio/wav">
        Your browser does not support the audio element.
</audio>

user_id=89
<audio controls>
        <source src="Results/converted_89_(9).wav" type="audio/wav">
        Your browser does not support the audio element.
</audio>


## Audio Samples for many-to-many

<table>
  <tr>
    <th>Target Speaker</th>
    <th>From Training</th>
    <th>From Unseen Speaker</th>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="Results_mult/19-227-0057.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult/converted_125_to_19.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult_un/converted_3112_to_19.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="Results_mult/26-495-0086.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult/converted_125_to_26.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult_un/converted_3112_to_26.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="Results_mult/27-124992-0072.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult/converted_125_to_27.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult_un/converted_3112_to_27.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="Results_mult/32-21625-0000.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult/converted_125_to_32.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult_un/converted_3112_to_32.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="Results_mult/39-121914-0003.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult/converted_125_to_39.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult_un/converted_3112_to_39.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="Results_mult/40-222-0038.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult/converted_125_to_40.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult_un/converted_3112_to_40.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="Results_mult/60-121082-0080.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult/converted_125_to_60.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult_un/converted_3112_to_60.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="Results_mult/78-368-0024.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult/converted_125_to_78.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult_un/converted_3112_to_78.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="Results_mult/83-3054-0004.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult/converted_125_to_83.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult_un/converted_3112_to_83.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td>
      <audio controls>
        <source src="Results_mult/87-121553-0103.flac" type="audio/flac">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult/converted_125_to_87.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls>
        <source src="Results_mult_un/converted_3112_to_87.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </td>
  </tr>                
</table>


This page presents our paper:

**Title:** Discrete Optimal Transport is a Strong Audio Adversarial Attack
**Authors:** Anton Selitskiy, Akib Shahriyar, and Jishnuraj Prakasan  
**PDF:** [Download paper](https://arxiv.org/abs/2509.14959)
**Code:** [on GitHub](https://github.com/anton-selitskiy/DOTattack)

## Abstract
In this paper, we introduce the discrete optimal transport voice
conversion (*k*DOT-VC) method. Comparison with *k*NN-VC,
SinkVC, and Gaussian optimal transport (factorized MKL) demon-
strates stronger domain adaptation abilities of our method.
We use the probabilistic nature of optimal transport (OT) and
show that *k*DOT-VC is an effective black-box adversarial attack
against modern audio anti-spoofing countermeasures (CMs).
Our attack operates as a post-processing, distribution-alignment
step: frame-level WavLM embeddings of generated speech are
aligned to an unpaired bona fide pool via entropic OT and a top-
*k* barycentric projection, then decoded with a neural vocoder.
Ablation analysis indicates that distribution-level alignment is a
powerful and stable attack for deployed CMs.

## Code
[GitHub Repository](https://github.com/anton-selitskiy/DOTattack)

## Audio Samples
Link to examples, or embed a player using HTML.
