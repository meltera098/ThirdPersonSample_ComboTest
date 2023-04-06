# ThirdPersonSample5_1

【UE5】GamePlayAbilitySystemによるコンボ攻撃の実装とそれに利用する小ネタ　後編【GAS】
https://lunanelis.hatenablog.com/entry/2022/06/13/041602

こちらのページに公開されているコンボ実装方法を自分で作ってみたところ、TickでTryActivateAbilitiesbyTagを呼ぶと
一部のタグが残ってしまう現象が起きたため、ネリス様に確認いただけるよう公開しました。

UE5のバージョンは5.1.0です。
アニメーションモンタージュやGameplayAbilityなどのアセットは、Content\Mannequinフォルダ内に入っています。
